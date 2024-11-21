---
title: Nguyên Tố Sét
description: 
published: true
date: 2024-11-21T04:06:11.961Z
tags: ele, lighting, sét, nguyên tố sét, choáng, knock back, đẩy lùi, bỏ qua phòng ngự
editor: markdown
dateCreated: 2024-11-09T18:27:32.779Z
---

> Chú Thích: `NTS` = Nguyên Tố Sét

| Hiệu ứng | Tác dụng đặc biệt | Ví dụ tham khảo |
|:---------|:------------------|:----------------|
| ![ele-lighting-spec.gif](/assets/elements/ele-lighting-spec.gif) | - `Choáng` đối phương trong `1s`.<br> - Khi bị `choáng` giảm `100%` khả năng `né tránh` và `100%` khả năng `block` đòn đánh của đối phương.<br>- Trong 5s hưởng hiệu ứng `30%` bỏ qua phòng thủ đối phương.<br>- Khi đối phương bị `crit dmg` từ nguyên tố này, sẽ bị knock back (đẩy lùi) 2-3 ô gì đó | Phù hợp với build có số hit đánh ra nhanh và nhiều |
Hai điều kiện để xuất hiện hiệu ứng đặc biệt `Choáng` là phải có 2 opt thuộc tính sau: 
- [Add `LIGHTING` element damage `x` (min) - `y` (max) *Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTS` lên đối phương.*](https://wiki.mu0rs.com/vi/elements#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2)
- [Increase `LIGHTING` special rate `x%`*Khi gây sát thương `NTS` có `x%` xuất hiện hiệu ứng đặt biệt: `Choáng`*](https://wiki.mu0rs.com/vi/elements#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3)
{.links-list}

> Nếu có nhiều hơn 1 loại Opt `Add element damage` hoặc `Increase element special rate` thì sẽ tính của Opt có giá trị cao hơn.
{.is-info}

# Op tấn công (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết | Tay | Vòng Cổ | Vũ Khí |
|:---------------|:----:|:------|:------|:---------|:---:|:-------:|:------:|
| Add `LIGHTING` element damage `x` - `y` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTS` lên đối phương. | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `LIGHTING` element special rate `x%` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương `NTS` có `x%` xuất hiện hiệu ứng đặt biệt: `Choáng` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `LIGHTING` element damage `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thêm sát thương `NTS` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `LIGHTING` element critical rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ sát thương `NTS` chí mạng `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `LIGHTING` element double rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ x2 sát thương `NTS` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `LIGHTING` element ignore rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ bỏ qua phòng ngự `NTS` `x%` .Bao gồm:<br>- Kháng (Resist) `NTS`.<br>- Phòng thủ(Defense) `NTS`.<br>- Né tránh (Dodge) `NTS`. | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `LIGHTING` element effect time `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thời gian tác dụng của hiệu ứng `Choáng` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease target `LIGHTING` element defense `x` | <span class="mdi mdi-sword"/> | - | - | Giảm `x` phòng thủ `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease target `LIGHTING` element absorb `x%` | <span class="mdi mdi-sword"/> | - | - | Giảm `x%` hấp thụ sát thương `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |

# Op phòng thủ (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết | Mũ | Áo | Quần | Chân | Nhẫn | Khiên |
|:---------------|:----:|:------|:------|:---------|:--:|:--:|:----:|:----:|:----:|:-----:|
| Add `LIGHTING` defense `x` | <span class="mdi mdi-shield"/> | - | - | Thêm `x` phòng thủ `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Absorb `LIGHTING` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Hấp thụ (giảm) `x%` sát thương `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `LIGHTING` element defense `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng `x%` phòng thủ `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Resist `LIGHTING` element effect `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` kháng hiệu ứng đặc biệt `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Absorb `LIGHTING` element damage to HP `x%`%| <span class="mdi mdi-shield"/> | - | - | Hấp thụ `x%` sát thương `NTS` sang Máu | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Max Resist `LIGHTING` element `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đá kháng `NTS` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Max Dodge `LIGHTING` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đa `x%` né sát thương `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease `LIGHTING` effect time `x%` | <span class="mdi mdi-shield"/> | - | - | Giảm `x%` thời gian dính hiệu ứng đặc biệt `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Dodge `LIGHTING` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` né sát thương `NTS` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |

# Liên quan
- [Elements](/vi/elements)
- [Fire Element](/vi/elements/fire)
- [Ice Element](/vi/elements/ice)
- [Posion Element](/vi/elements/posion)
{.links-list}