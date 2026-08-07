# Jenkins

## Jenkins Nedir?

Jenkins, Continuous Integration (CI) ve Continuous Delivery (CD) süreçlerini otomatikleştiren açık kaynaklı bir otomasyon sunucusudur.

## Jenkinsfile

Jenkins Pipeline tanımları Jenkinsfile içerisinde tutulur.

## Pipeline

Bu projede aşağıdaki Pipeline örneği hazırlanmıştır.

```
Build
   ↓
Test
   ↓
Deploy
```

## Stage

Her işlem ayrı bir Stage içerisinde tanımlanır.

- Build
- Test
- Deploy

## Agent

Pipeline'ın hangi makinede çalışacağını belirtir.

Bu projede:

```groovy
agent any
```

kullanılmıştır.

## Post

Pipeline tamamlandıktan sonra çalışacak işlemler tanımlanabilir.

- Success
- Failure

## Avantajları

- Otomatik build
- Otomatik test
- Hızlı deployment
- Sürekli entegrasyon
- Daha az manuel işlem