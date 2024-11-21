---
title: Nguyên Tố Băng
description: 
published: true
date: 2024-11-21T04:03:02.489Z
tags: ele, ice, special, băng, nguyên tố băng, hiệu ứng đặc biệt, đóng băng, làm chậm
editor: markdown
dateCreated: 2024-11-09T18:30:18.858Z
---

> Chú Thích: `NTB` = Nguyên Tố Băng

| Hiệu ứng | Tác dụng đặc biệt | Ví dụ tham khảo |
|:---------|:------------------|:----------------|
| ![ele-ice-spec.gif](/assets/elements/ele-ice-spec.gif) | - `Đóng băng` đối phương `0.5s` sau đó `làm chậm` trong `7s`. <br>- Khi bị `đóng băng` giảm `100%` khả năng `né tránh` và `100%` khả năng `block` đòn đánh của đối phương.<br>- Sát thương bị gây khi đối phương trong trạng thái `làm chậm`, sẽ tăng thêm `50%` tỉ lệ xuất hiện sát thương hoàn hảo. | Phù hợp với các build gây sát thương liên tục thật nhanh, hoặc cần phá block ( đỡ đòn từ khiên ), phá né của đối phương. |

Hai điều kiện để xuất hiện hiệu ứng đặc biệt `Đóng băng` là phải có 2 opt thuộc tính sau: 
- [Add `ICE` element damage `x` (min) - `y` (max) *Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTB` lên đối phương.*](https://wiki.mu0rs.com/vi/elements#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2)
- [Increase `ICE` special rate `x%`*Khi gây sát thương `NTB` có `x%` xuất hiện hiệu ứng đặt biệt: `Đóng băng`*](https://wiki.mu0rs.com/vi/elements#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3)
{.links-list}

> Nếu có nhiều hơn 1 loại Opt `Add element damage` hoặc `Increase element special rate` thì sẽ tính của Opt có giá trị cao hơn.
{.is-info}

# Op tấn công (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết | Tay | Vòng Cổ | Vũ Khí |
|:---------------|:----:|:------|:------|:---------|:---:|:-------:|:------:|
| Add `ICE` element damage `x` - `y` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTB` lên đối phương. | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `ICE` element special rate `x%` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương `NTB` có `x%` xuất hiện hiệu ứng đặt biệt: `Đóng băng` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `ICE` element damage `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thêm sát thương `NTB` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `ICE` element critical rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ sát thương `NTB` chí mạng `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `ICE` element double rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ x2 sát thương `NTB` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `ICE` element ignore rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ bỏ qua phòng ngự `NTB` `x%` .Bao gồm:<br>- Kháng (Resist) `NTB`.<br>- Phòng thủ(Defense) `NTB`.<br>- Né tránh (Dodge) `NTB`. | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `ICE` element effect time `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thời gian tác dụng của hiệu ứng `Đóng băng` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease target `ICE` element defense `x` | <span class="mdi mdi-sword"/> | - | - | Giảm `x` phòng thủ `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease target `ICE` element absorb `x%` | <span class="mdi mdi-sword"/> | - | - | Giảm `x%` hấp thụ sát thương `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |

# Op phòng thủ (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết | Mũ | Áo | Quần | Chân | Nhẫn | Khiên |
|:---------------|:----:|:------|:------|:---------|:--:|:--:|:----:|:----:|:----:|:-----:|
| Add `ICE` defense `x` | <span class="mdi mdi-shield"/> | - | - | Thêm `x` phòng thủ `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Absorb `ICE` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Hấp thụ (giảm) `x%` sát thương `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `ICE` element defense `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng `x%` phòng thủ `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Resist `ICE` element effect `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` kháng hiệu ứng đặc biệt `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Absorb `ICE` element damage to HP `x%`%| <span class="mdi mdi-shield"/> | - | - | Hấp thụ `x%` sát thương `NTB` sang Máu | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Max Resist `ICE` element `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đá kháng `NTB` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Max Dodge `ICE` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đa `x%` né sát thương `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease `ICE` effect time `x%` | <span class="mdi mdi-shield"/> | - | - | Giảm `x%` thời gian dính hiệu ứng đặc biệt `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Dodge `ICE` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` né sát thương `NTB` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |

# Liên quan
- [Elements](/vi/elements)
- [Fire](/vi/elements/fire)
- [Lighting](/vi/elements/lighting)
- [Posion](/vi/elements/posion)
{.links-list}