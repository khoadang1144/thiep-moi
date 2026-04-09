# Thiep Moi

Bo file nay la mot website tinh. Cach de nhat de co link public la dung GitHub Pages.

## Cach lam nhanh

1. Tao mot repository moi tren GitHub, vi du `thiep-moi` trong tai khoan `khoadang1144`.
2. Mo terminal tai thu muc nay va chay:

```bash
git init
git add .
git commit -m "Initial invitation site"
git branch -M main
git remote add origin https://github.com/khoadang1144/thiep-moi.git
git push -u origin main
```

3. Tren GitHub vao:
   Settings -> Pages

4. O `Build and deployment`:
   Source: `Deploy from a branch`
   Branch: `main`
   Folder: `/ (root)`

5. Sau khi GitHub Pages build xong, ban se co link dang:

```text
https://khoadang1144.github.io/thiep-moi/thong-tin-buoi-tiec.html
```

## Link can dan vao trang tao QR

Sau khi co link public, mo `thiep-moi.html` va dan link nay vao o `Link cong khai cua thiep`:

```text
https://khoadang1144.github.io/thiep-moi/thong-tin-buoi-tiec.html
```

Luc do moi QR se tro den link public va khach co the quet tren dien thoai bat cu luc nao.

## Vi du link moi khach

Sau khi dan link public, he thong se tao link dang:

```text
https://khoadang1144.github.io/thiep-moi/thong-tin-buoi-tiec.html?khach-moi=Gia+Huy&ma-khach=guest-001
```

Link nay mo ra trang rieng cua khach do.

Neu ban dat ten repository khac `thiep-moi`, hay doi phan `thiep-moi` trong cac link va lenh tren thanh ten repository thuc te.