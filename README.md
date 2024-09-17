# Introduction
Modulo manageer desde donde se va centralizar todos los manifiestos de los microservicios relacionados a cuenta unica

# Procedimiento ejecucion inicial
El contenido del directorio /manager/init debe ejecutarse manualmente

kubectl apply -f sunat-project-cuentaunica.yaml

#Para develop
kubectl apply -f dev/sunat-repo-gitops.yaml

#Para qa
kubectl apply -f qa/sunat-repo-gitops.yaml

