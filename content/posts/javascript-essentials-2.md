---
title: "JavaScript Essentials 2 – DOM & Bất đồng bộ"
date: 2024-05-08T00:00:00+07:00
draft: false
description: "Khóa học phần 2: Thao tác DOM, sự kiện, storage và gọi API bất đồng bộ."
showToc: true
showBreadCrumbs: true
showReadingTime: true
---

## Giới thiệu
Phần 2 tập trung vào việc kết nối JavaScript với giao diện và dữ liệu thật. Bạn sẽ học cách thao tác DOM, lắng nghe sự kiện, lưu trữ dữ liệu phía trình duyệt và gọi API bằng Promise/async‑await.

## Mục tiêu học tập
- Hiểu và thao tác DOM một cách hiệu quả.
- Quản lý sự kiện, delegate sự kiện trong danh sách động.
- Sử dụng `localStorage`/`sessionStorage` cho trạng thái người dùng.
- Gọi API với Fetch, xử lý lỗi, loading và timeout.

## Nội dung chi tiết
### 1) DOM căn bản
- Chọn phần tử: `getElementById`, `querySelector(All)`.
- Duyệt cây DOM, thêm/sửa/xóa node.
- ClassList, style, thuộc tính dataset.

### 2) Sự kiện
- Các sự kiện phổ biến: click, input, submit, keydown.
- Ngăn chặn mặc định (preventDefault), dừng nổi bọt (stopPropagation).
- Ủy quyền sự kiện (event delegation) cho danh sách.

### 3) Storage & State
- `localStorage` vs `sessionStorage` và cookies cơ bản.
- Lưu trạng thái theme, form draft, giỏ hàng mini.

### 4) Bất đồng bộ & API
- Promise, chain Promise, error handling.
- `async/await`, try/catch; AbortController hủy request.
- Fetch API: GET/POST, headers, JSON, xử lý lỗi HTTP.

## Bài tập thực hành
- Gallery động: lọc/phan trang client, mở lightbox.
- Form validation: kiểm tra input, hiển thị message.
- Gọi API công khai: hiển thị dữ liệu, xử lý loading/error.

## Kết luận
Sau phần 2, bạn có thể xây dựng giao diện tương tác, đồng bộ dữ liệu với server và quản lý trạng thái trên trình duyệt. Tiếp tục luyện tập bằng các mini‑project để củng cố kiến thức.
