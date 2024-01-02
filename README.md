# HELMCHARTY do projektu news-processor

## generowanie charta

- ustaw się w katalogu z chartem i wykonaj:
  `helm package .`
## wrzucanie na klaster k8s

- klaster musi byc skonfigurowany w ~/.kube/config

  `helm apply -e dev`

## usuwanie: 
`helmfile delete -e dev
`
