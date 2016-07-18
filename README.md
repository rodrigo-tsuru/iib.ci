# iib.ci
Scripts baseados no artigo https://developer.ibm.com/integration/blog/2015/10/02/continuous-build-and-deploy-automation-with-ibm-integration-bus-v10-using-ant-git-and-jenkins/

# Pré-requisitos
Antes de rodar os scripts verifique se os seguintes softwares estão instalados:

1. Apache Ant
2. IBM Integration Bus Developer Edition v10 (http://public.dhe.ibm.com/ibmdl/export/pub/software/websphere/integration/10.0.0.4-IIB-LINUX64-DEVELOPER.tar.gz)

# Procedimento de execução
1. Faça o clone deste repositório
2. Rode o build:
```bash
ant -f build_main.xml
```
