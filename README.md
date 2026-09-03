# ExamSheet cho macOS

Repo này sẽ host **bản cài đặt macOS** và **kênh cập nhật tự động** cho ExamSheet.

## Chưa có bản phát hành

ExamSheet hiện **chưa có bản cho macOS**. Repo được tạo sẵn để khi có bản Mac thì
kênh cập nhật đã nằm đúng chỗ ngay từ đầu — địa chỉ appcast được biên dịch thẳng
vào từng bản phát hành, nên **đổi chỗ về sau là làm hỏng đường cập nhật của mọi
máy đã cài**.

File `.gitattributes` đã có sẵn từ commit đầu tiên và **không được xoá**: nó ghim
`appcast*.xml` ở chế độ nhị phân. Thiếu nó thì git tự đổi ký tự xuống dòng, chữ ký
Ed25519 lệch, và ứng dụng vĩnh viễn không thấy bản cập nhật — **không một thông báo
lỗi nào chỉ ra nguyên nhân**.

## Bản quyền

Copyright © 2026 RuBi. All rights reserved.
