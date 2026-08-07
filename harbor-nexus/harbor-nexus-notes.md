# Harbor ve Nexus

## Harbor Nedir?

Harbor, Docker ve OCI uyumlu container image'larını güvenli şekilde saklamak için kullanılan açık kaynaklı bir registry'dir.

### Harbor Özellikleri

- Docker Image Repository
- OCI Registry desteği
- Kullanıcı ve yetkilendirme
- Vulnerability Scan
- Image Replication
- Web arayüzü

---

## Nexus Nedir?

Nexus Repository Manager, farklı yazılım paketlerini ve artifact'leri merkezi olarak saklamak için kullanılan bir artifact repository'dir.

### Nexus Özellikleri

- Maven Repository
- Gradle Repository
- npm Repository
- NuGet Repository
- Docker Repository
- Proxy Repository

---

# OCI Registry Nedir?

OCI (Open Container Initiative) Registry, container image'larının standart bir formatta saklanmasını sağlayan registry yapısıdır.

Örnek:

- Docker Hub
- Harbor
- GitHub Container Registry

---

# Docker Image Repository

Docker image'larının saklandığı depodur.

Örneğin:

```
nginx:latest
springboot-api:v1
frontend:v2
```

---

# Artifact Repository

Artifact Repository yalnızca Docker image değil;

- jar
- war
- zip
- npm package
- Maven package
- NuGet package

gibi yazılım çıktılarının saklandığı merkezi depodur.

---

# Vulnerability Scan

Harbor image'ları güvenlik açıklarına karşı tarayabilir.

Örneğin:

- High
- Medium
- Low

seviyelerinde güvenlik açıklarını raporlayabilir.

---

# Harbor ve Nexus Karşılaştırması

| Özellik | Harbor | Nexus |
|----------|---------|--------|
| Docker Image | ✅ | ✅ |
| OCI Registry | ✅ | ✅ |
| Maven Repository | ❌ | ✅ |
| npm Repository | ❌ | ✅ |
| NuGet Repository | ❌ | ✅ |
| Vulnerability Scan | ✅ | ❌  |
| Web Arayüzü | ✅ | ✅ |

---

# Sonuç

Harbor daha çok container image yönetimi için kullanılır.

Nexus ise yazılım geliştirme sürecinde oluşan farklı artifact türlerini merkezi olarak yönetmek için kullanılır.