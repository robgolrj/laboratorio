# laboratorio
laboratório para comandos git

Forçar o Git a processar, mas não fazer checkout, do histórico completo de cada branch e tag
Remover o arquivo especificado, bem como qualquer commit vazio gerado como resultado

$ git filter-branch --force --index-filter \
  "git rm --cached --ignore-unmatch PATH-TO-YOUR-FILE-WITH-SENSITIVE-DATA" \
  --prune-empty --tag-name-filter cat -- --all

Push do origin
git push origin --force --all  

Forçando atualização das tags
git push origin --force --tags

