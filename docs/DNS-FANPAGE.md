# DNS — fanpage.infi.io.vn → Vercel (P0023-Fanpage-Dashboard)

Production app: **https://fanpage.infi.io.vn**  
Vercel fallback: **https://p0023-fanpage-dashboard.vercel.app**

## Tino DNS (subdomain)

| Loại | Host | Giá trị |
|------|------|---------|
| **A** | `fanpage.infi.io.vn` | `76.76.21.21` |

## Kiểm tra

```powershell
Resolve-DnsName fanpage.infi.io.vn -Type A
(Invoke-WebRequest -Uri "https://fanpage.infi.io.vn" -UseBasicParsing).StatusCode
# 200
```
