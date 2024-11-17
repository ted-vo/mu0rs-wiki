---
title: Nguyên Tố Lửa
description: 
published: true
date: 2024-11-17T11:05:56.428Z
tags: ele, fire, special
editor: markdown
dateCreated: 2024-11-09T18:24:29.011Z
---

| Hiệu ứng | Tác dụng đặc biệt | Ví dụ tham khảo |
|:---------|:------------------|:------|
| ![ele-fire-spec.gif](/assets/elements/ele-fire-spec.gif) | - `Đốt cháy` đối phương.<br>- Gây sát thương đốt máu liên tục. Sát thương đốt cháy dựa vào sát thương gây ra cuối cùng của đòn đánh (kỹ năng).<br>- Giảm giáp đối phương. | Phù hợp kiểu build có dame kết thúc lớn. 


Điều Kiện cần để xuất hiện hiệu ứng đặc biệt `Đốt Cháy` là phải có cái Opt thuộc tính sau: 
- [Add `FIRE` element damage `x` (min) - `y` (max) *E1/E2*](https://wiki.mu0rs.com/vi/elements#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2)
- [Increase `FIRE` special rate `x%`*E3*](https://wiki.mu0rs.com/vi/elements#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3)
{.links-list}

> Nếu có nhiều hơn 1 loại Opt `Add element damage` hoặc `Increase special rate` thì sẽ tính của Opt có giá trị cao hơn.
{.is-info}

# Op tấn công (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết |
|:---------------|:----:|:------|:------|:---------|
| Add `FIRE` element damage `x` - `y` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương sẽ có thêm `x` - `y` sát thương thuộc tính `Lửa` lên đối phương.<br>Opt này là điều kiện cần để kích hoạt khả năng xuất hiện hiệu ứng đặc biệt `Đốt Cháy` của `Nguyên Tố Lửa`. |
| Increase `FIRE` element special rate `x%` | <span class="mdi mdi-sword"/> | - | - | Khi gây sát thương nguyên tố `Lửa` có `x%` xuất hiện hiệu ứng đặt biệt: `Đốt Cháy` |
| Increase `FIRE` element damage `x%` | <span class="mdi mdi-sword"/> | - | - | - |
| Increase `FIRE` element critical rate `x%` | <span class="mdi mdi-sword"/> | - | - | - |
| Increase `FIRE` element double rate `x`% | <span class="mdi mdi-sword"/> | - | - | - |
| Increase `FIRE` element ignore rate `x`% | <span class="mdi mdi-sword"/> | - | - | - |
| Increase `FIRE` element effect time `x`% | <span class="mdi mdi-sword"/> | - | - | - |
| Decrease target `FIRE` element defense `x` | <span class="mdi mdi-sword"/> | - | - | - |
| Decrease target `FIRE` element absorb `x%` | <span class="mdi mdi-sword"/> | - | - | - |

# Op phòng thủ (E1/E2)

| Opt thuộc tinh | Loại | Min x | Max y | Chi Tiết |
|:---------------|:----:|:------|:------|:---------|
| Add `FIRE` defense `x` | <span class="mdi mdi-shield"/> | - | - | - |
| Absorb `FIRE` element damage `x`% | <span class="mdi mdi-shield"/> | - | - | - |
| Increase `FIRE` element defense `x`% | <span class="mdi mdi-shield"/> | - | - | - |
| Resist `FIRE` element effect `x`% | <span class="mdi mdi-shield"/> | - | - | - |
| Absorb `FIRE` element damage to HP `x`% | <span class="mdi mdi-shield"/> | - | - | - |
| Max Resist `FIRE` element `x`% | <span class="mdi mdi-shield"/> | - | - | - |
| Max Dodge `FIRE` element damage `x`% | <span class="mdi mdi-shield"/> | - | - | - |
| Decrease `FIRE` effect time `x`% | <span class="mdi mdi-shield"/> | - | - | - |
| Dodge `FIRE` element damage `x`% | <span class="mdi mdi-shield"/> | - | - | - |

# Liên quan
- [Elements](/vi/elements)
- [Ice](/vi/elements/ice)
- [Lighting](/vi/elements/lighting)
- [Posion](/vi/elements/posion)
{.links-list}