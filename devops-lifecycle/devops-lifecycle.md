# Developer'dan Production'a DevOps Yaşam Döngüsü

## DevOps Süreci

Modern yazılım geliştirme süreçlerinde kodun production ortamına ulaşması birçok otomatik adımdan geçer.

Bu projede örnek DevOps yaşam döngüsü aşağıdaki gibidir.

1. Developer kod geliştirir.
2. Kod GitHub'a gönderilir.
3. Jenkins Pipeline çalışır.
4. Docker Image oluşturulur.
5. Harbor Repository'ye yüklenir.
6. Helm Chart kullanılarak Kubernetes manifestleri hazırlanır.
7. ArgoCD Git deposunu izler.
8. Kubernetes cluster uygulamayı otomatik olarak günceller.
9. Uygulama Production ortamında çalışır.

## Kullanılan Araçlar

- Git
- GitHub
- Jenkins
- Docker
- Harbor
- Helm
- ArgoCD
- Kubernetes