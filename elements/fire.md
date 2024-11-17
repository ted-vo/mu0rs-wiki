---
title: Nguyên Tố Lửa
description: 
published: true
date: 2024-11-17T11:52:51.556Z
tags: ele, fire, special
editor: markdown
dateCreated: 2024-11-09T18:24:29.011Z
---

> Chú Thích: `NTL` = Nguyên Tố Lửa

| Hiệu ứng | Tác dụng đặc biệt | Ví dụ tham khảo |
|:---------|:------------------|:------|
| ![ele-fire-spec.gif](/assets/elements/ele-fire-spec.gif) | - `Đốt cháy` đối phương.<br>- Gây sát thương đốt máu liên tục. Sát thương đốt cháy dựa vào sát thương gây ra cuối cùng của đòn đánh (kỹ năng).<br>- Giảm giáp đối phương. | Phù hợp kiểu build có dame kết thúc lớn. |

Điều Kiện cần để xuất hiện hiệu ứng đặc biệt `Đốt Cháy` là phải có cái Opt thuộc tính sau: 
- [Add `FIRE` element damage `x` (min) - `y` (max) *Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTL` lên đối phương.*](https://wiki.mu0rs.com/vi/elements#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2)
- [Increase `FIRE` special rate `x%`*Khi gây sát thương `NTL` có `x%` xuất hiện hiệu ứng đặt biệt: `Đốt Cháy`*](https://wiki.mu0rs.com/vi/elements#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3)
{.links-list}

> Nếu có nhiều hơn 1 loại Opt `Add element damage` hoặc `Increase element special rate` thì sẽ tính của Opt có giá trị cao hơn.
{.is-info}

# Op tấn công (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết |
|:---------------|:----:|:------|:------|:---------|
| Add `FIRE` element damage `x` - `y` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương sẽ có thêm `x` - `y` sát thương `NTL` lên đối phương. |
| Increase `FIRE` element special rate `x%` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương `NTL` có `x%` xuất hiện hiệu ứng đặt biệt: `Đốt Cháy` |
| Increase `FIRE` element damage `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thêm sát thương `NTL` `x%` |
| Increase `FIRE` element critical rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ sát thương `NTL` chí mạng `x%` |
| Increase `FIRE` element double rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ x2 sát thương `NTL` `x%` |
| Increase `FIRE` element ignore rate `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng tỉ lệ bỏ qua phòng ngự `NTL` `x%` .Bao gồm:<br>- Kháng (Resist) `NTL`.<br>- Phòng thủ(Defense) `NTL`.<br>- Né tránh (Dodge) `NTL`. |
| Increase `FIRE` element effect time `x%` | <span class="mdi mdi-sword"/> | - | - | Tăng thời gian tác dụng của hiệu ứng `Đốt Cháy` `x%` |
| Decrease target `FIRE` element defense `x` | <span class="mdi mdi-sword"/> | - | - | Giảm `x` phòng thủ `NTL` |
| Decrease target `FIRE` element absorb `x%` | <span class="mdi mdi-sword"/> | - | - | Giảm `x%` hấp thụ sát thương `NTL` |

# Op phòng thủ (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết |
|:---------------|:----:|:------|:------|:---------|
| Add `FIRE` defense `x` | <span class="mdi mdi-shield"/> | - | - | Thêm `x` phòng thủ `NTL` |
| Absorb `FIRE` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Hấp thụ (giảm) `x%` sát thương `NTL` |
| Increase `FIRE` element defense `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng `x%` phòng thủ `NTL` |
| Resist `FIRE` element effect `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` kháng hiệu ứng đặc biệt `NTL` |
| Absorb `FIRE` element damage to HP `x%`%| <span class="mdi mdi-shield"/> | - | - | Hấp thụ `x%` sát thương `NTL` sang Máu |
| Max Resist `FIRE` element `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đá kháng `NTL` `x%` |
| Max Dodge `FIRE` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | Tăng tối đa `x%` né sát thương `NTL` |
| Decrease `FIRE` effect time `x%` | <span class="mdi mdi-shield"/> | - | - | Giảm `x%` thời gian dính hiệu ứng đặc biệt `NTL` |
| Dodge `FIRE` element damage `x%` | <span class="mdi mdi-shield"/> | - | - | `x%` né sát thương `NTL` |

# Liên quan
- [Elements](/vi/elements)
- [Ice](/vi/elements/ice)
- [Lighting](/vi/elements/lighting)
- [Posion](/vi/elements/posion)
{.links-list}