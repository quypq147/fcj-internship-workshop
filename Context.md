# Context for GitHub Copilot

Dự án này là một trang tài liệu/workshop sử dụng Hugo. Dưới đây là cấu trúc template Markdown chuẩn dùng cho các bài viết và workshop trong dự án. Khi tạo nội dung mới, hãy tuân thủ cấu trúc Frontmatter và các thành phần định dạng (Heading, Shortcode) như mẫu dưới đây.

---

## Mẫu Template Bài Viết (Page/Workshop Template)

```markdown
---
title: "[Nhập Tiêu đề bài viết tại đây]"
date: 2024-01-01
weight: [Nhập số thứ tự menu]
chapter: false
pre: " <b> [Nhập số thứ tự chương]. </b> "
---

# [Nhập Tiêu đề chính của Bài Lab / Workshop]

#### Tổng quan

[Viết đoạn giới thiệu tổng quan về dịch vụ hoặc công nghệ sẽ thực hành]

[Viết đoạn mô tả mục tiêu của bài lab và những gì người dùng sẽ đạt được]

[Liệt kê các khái niệm hoặc các thành phần chính nếu có]
+ **[Tên thành phần/Khái niệm 1]** - [Mô tả chi tiết]
+ **[Tên thành phần/Khái niệm 2]** - [Mô tả chi tiết]

#### Nội dung

1. [Tổng quan về workshop]([link-thu-muc-1]/)
2. [Chuẩn bị]([link-thu-muc-2]/)
3. [[Tên Bước Thực Hành 1]]([link-thu-muc-3]/)
4. [[Tên Bước Thực Hành 2]]([link-thu-muc-4]/)
5. [[Phần Mở Rộng - Nếu có]]([link-thu-muc-5]/)
6. [Dọn dẹp tài nguyên]([link-thu-muc-cleanup]/)