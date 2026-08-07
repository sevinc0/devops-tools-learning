# ArgoCD

## ArgoCD Nedir?

ArgoCD, Kubernetes için geliştirilmiş açık kaynaklı bir Continuous Delivery (CD) aracıdır. GitOps yaklaşımını kullanarak Git deposundaki değişiklikleri otomatik olarak Kubernetes ortamına uygular.

## GitOps Nedir?

GitOps, altyapı ve uygulama yapılandırmalarının Git deposunda tutulduğu ve değişikliklerin Git üzerinden yönetildiği bir yaklaşımdır.

## ArgoCD Application

Bu projede örnek bir Application tanımı hazırlanmıştır.

Application dosyası;

- GitHub repository'sini izler.
- Helm Chart'ı kullanır.
- Kubernetes cluster'ına deploy eder.

## Sync Policy

Automatic Sync etkin olduğunda:

- Git değişiklikleri otomatik uygulanır.
- Hatalı değişiklikler düzeltilebilir (Self Heal).
- Kullanılmayan kaynaklar temizlenebilir (Prune).

## Avantajları

- GitOps yaklaşımı
- Otomatik deployment
- Versiyon kontrolü
- Kolay rollback
- Kubernetes ile tam uyum