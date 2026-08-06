# Helm Nedir?

Helm, Kubernetes için paket yöneticisidir.

Helm sayesinde Kubernetes uygulamaları Chart adı verilen paketler halinde yönetilebilir.

## Bu projede bulunan dosyalar

- Chart.yaml
- values.yaml
- templates/deployment.yaml
- templates/service.yaml

## Kullanılan Helm Komutları

```bash
helm create nginx-chart
helm template nginx-chart .
helm install nginx-chart .
```

## Avantajları

- YAML tekrarını azaltır.
- Parametre yönetimini kolaylaştırır.
- Uygulama güncellemelerini kolaylaştırır.
- Kubernetes uygulamalarını standart hale getirir.