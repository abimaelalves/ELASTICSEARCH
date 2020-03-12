# Script para automatizar o backup do Elasticsearch rodando em container do docker

# Configuração do CRON de backup e conferencia do backup: 

# 0 1 * * 0 CAMINHOdoVOLUME/elasticsearch/doSnapshot > CAMINHOdoVOLUME/elasticsearch/doSnapshot.log 2>&1
# 0 5 * * 0 CAMINHOdoVOLUME/elasticsearch/confereSnapshot > CAMINHOdoVOLUME/elasticsearch/confereSnapshot.log 2>&1
