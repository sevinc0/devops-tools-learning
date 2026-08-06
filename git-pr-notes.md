# Git ve Pull Request Süreci

## Git Nedir?

Git, yazılım geliştirme sürecinde kullanılan dağıtık bir versiyon kontrol sistemidir. Kod değişikliklerini takip etmeyi, önceki sürümlere dönmeyi ve ekip çalışmasını kolaylaştırır.

## Pull Request Nedir?

Pull Request (PR), bir branch üzerinde yapılan değişikliklerin başka bir branch'e eklenmesi için oluşturulan istektir. PR süreci sayesinde kodlar incelenebilir, yorum yapılabilir ve onaylandıktan sonra ana dala (main) birleştirilebilir.

## Uygulanan Adımlar

1. Yeni bir Git deposu oluşturuldu (`git init`).
2. README.md dosyası eklendi.
3. İlk commit oluşturuldu.
4. Proje GitHub'a gönderildi.
5. `git-pr-demo` isimli yeni bir branch oluşturuldu.
6. README.md dosyası güncellendi.
7. Değişiklikler commit edilerek GitHub'a gönderildi.
8. GitHub üzerinde Pull Request oluşturuldu.
9. Pull Request başarıyla merge edilerek `main` branch'ine aktarıld.

## Kullanılan Git Komutları

```bash
git init
git add .
git commit -m "Initial DevOps tools project"
git checkout -b git-pr-demo
git add .
git commit -m "Add Git PR demo section"
git push -u origin git-pr-demo
```

## Sonuç

Bu çalışma ile Git kullanımı, branch oluşturma, commit işlemleri, GitHub'a kod gönderme, Pull Request açma ve merge etme süreçleri uygulamalı olarak gerçekleştirilmiştir.