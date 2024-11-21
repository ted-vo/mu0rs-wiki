---
title: Nguyên Tố Độc
description: 
published: true
date: 2024-11-21T03:59:32.065Z
tags: ele, posion, special
editor: markdown
dateCreated: 2024-11-09T18:39:09.408Z
---

> Chú Thích: `NTĐ` = Nguyên Tố Độc

| Hiệu ứng | Tác dụng đặc biệt | Ví dụ tham khảo |
|:---------|:------------------|:------|
| ![ele-posion-spec.gif](/assets/elements/ele-posion-spec.gif) | - `Dính độc`, rút máu.<br>- Giảm né của đối phương 30%. <br>- Giảm hồi máu đối phương 50% (giống hiệu ứng `Vết Thương Sâu` của LOL hay hiệu ứng của `Eye of Skadi` bên DotA 2  | Phù hợp khi đối đầu với đối thủ nhiều máu. |

Hai điều kiện để xuất hiện hiệu ứng đặc biệt `Dính độc` là phải có 2 opt thuộc tính sau: 
- [Add `POSION` element damage `x` (min) - `y` (max) *Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTĐ` lên đối phương.*](https://wiki.mu0rs.com/vi/elements#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2)
- [Increase `POSION` special rate `x%`*Khi gây sát thương `NTĐ` có `x%` xuất hiện hiệu ứng đặt biệt: `Dính độc`*](https://wiki.mu0rs.com/vi/elements#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3)
{.links-list}

> Nếu có nhiều hơn 1 loại Opt `Add element damage` hoặc `Increase element special rate` thì sẽ tính của Opt có giá trị cao hơn.
{.is-info}

# Op tấn công (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết | Tay | Vòng Cổ | Vũ Khí |
|:---------------|:----:|:------|:------|:---------|:---:|:-------:|:-------:
| Add `POSION` element damage `x` - `y` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTĐ` lên đối phương. | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `POSION` element special rate `x%` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương `NTĐ` có `x%` xuất hiện hiệu ứng đặt biệt: `Dính độc` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `POSION` element damage `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thêm sát thương `NTĐ` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `POSION` element critical rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ sát thương `NTĐ` chí mạng `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `POSION` element double rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ x2 sát thương `NTĐ` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `POSION` element ignore rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ bỏ qua phòng ngự `NTĐ` `x%` .Bao gồm:<br>- Kháng (Resist) `NTĐ`.<br>- Phòng thủ(Defense) `NTĐ`.<br>- Né tránh (Dodge) `NTĐ`. | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `POSION` element effect time `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thời gian tác dụng của hiệu ứng `Dính độc` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease target `POSION` element defense `x` | <span class="mdi mdi-sword"/> | - | - | Giảm `x` phòng thủ `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease target `POSION` element absorb `x%` | <span class="mdi mdi-sword"/> | - | - | Giảm `x%` hấp thụ sát thương `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |

# Op phòng thủ (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết | Mũ | Áo | Quần | Chân | Nhẫn | Khiên |
|:---------------|:----:|:------|:------|:---------|:--:|:--:|:----:|:----:|:----:|:-----:|
| Add `POSION` defense `x` | <span class="mdi mdi-shield"/> | - | - | Thêm `x` phòng thủ `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Absorb `POSION` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Hấp thụ (giảm) `x%` sát thương `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Increase `POSION` element defense `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng `x%` phòng thủ `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Resist `POSION` element effect `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` kháng hiệu ứng đặc biệt `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Absorb `POSION` element damage to HP `x%`%| <span class="mdi mdi-shield"/> | - | - | Hấp thụ `x%` sát thương `NTĐ` sang Máu | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Max Resist `POSION` element `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đá kháng `NTĐ` `x%` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Max Dodge `POSION` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đa `x%` né sát thương `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Decrease `POSION` effect time `x%` | <span class="mdi mdi-shield"/> | - | - | Giảm `x%` thời gian dính hiệu ứng đặc biệt `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |
| Dodge `POSION` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` né sát thương `NTĐ` | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> |

# Liên quan
- [Elements](/vi/elements)
- [Fire Element](/vi/elements/fire)
- [Ice Element](/vi/elements/ice)
- [Lighting Element](/vi/elements/lighting)
{.links-list}