# AutoJMS-plugins

Repo này **chỉ chứa gói phát hành** (GitHub Releases) của các plug-in AutoJMS. Source nằm ở repo riêng.

AutoJMS (tier ULTRA) cài plug-in ở tab **ABOUT → Thêm plug-in → Từ GitHub**: app đọc release mới nhất của repo này,
tải file `.zip`, đối chiếu SHA-256 với `SHA256SUMS.txt` của cùng release rồi mới cài.

## Quy ước mỗi release

- Tag: `<id>-v<version>`, ví dụ `autojms-login-v2.0.0`.
- Đúng **một** file `<id>-<version>.zip`, ở gốc zip có `plugin.json` (`id`, `name`, `version`, `entry`, `scenario`).
- `SHA256SUMS.txt`: dòng `<sha256> *<tên zip>`.

| id | Plug-in |
|---|---|
| `autojms-login` | Tự đăng nhập JMS (thanh trượt captcha + mã xác minh qua mail) |
