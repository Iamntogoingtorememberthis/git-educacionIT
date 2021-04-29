# Comandos de clase
    
    git clone url                > Clonamos repositorio remoto
    git add archivo              > Agregamos al staging area
    git add commit               > Agregamos a base de datos con mensaje descriptivo
    git commit --amend           > Corregir ultimo msje de commit

# primer caso, cuando guardamos, cerramos editor y NO agregamos a Staging Area 
    git diff                     > Revisar si hay diferencias entre archivos guardados y actuales
    git checkout --archivo       > Volver al archivo antes del cambio. Un ctrl+Z en git
# segundo caso, cuando guardamos, cerramos editor y SI agregamos a Staging Area
    git diff                     > Revisar si hay diferencias entre archivos guardados y actuales
    git restore --staged archivo > 
    git checkout -- archivo      >
# tercer caso, cuando gusrdamos, cerramos editor, agregamos al SA y Comiteamos
    git reset --hard (hash al que queremos volver)