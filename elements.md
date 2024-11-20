---
title: Hệ Thống Thuộc Tính
description: Hệ thống thuộc tính là một tính năng customize có một không hai của Mu0rs.com
published: true
date: 2024-11-20T15:50:10.817Z
tags: ele, posion, lighting, fire, ice, element, jewel element, độc, sét, lửa, băng, ngọc thuộc tính
editor: markdown
dateCreated: 2024-11-07T08:25:00.416Z
---

# Giới Thiệu
> Element  ([Thuộc tính, nguyên tố](#thuoc-tinh)) là gì ?
>
> Chắc các bạn từng biết ở 20+ năm về trước, khi diablo ra đời, trong game play của dibalo có các thuộc tính gọi là băng , lửa , điện ,độc v.v... Sau này, game Mu Online ra đời, cũng dựa trên 1 số cái của diablo. Và việc webzen đưa các thuộc tính vào trong mu online là có từ rất lâu rồi. Nếu các bạn để ý lại, sẽ thấy các skill của DW, nào là lửa, độc, điện , băng v.v.... các skill của DK cũng có thuộc tính đó, khi các bạn chỉ chuột vào các skill , sẽ thấy thuộc tính của skill đó là gì. Rồi kèm theo đó, là có các chiếc nhẫn như Ring Of Fire (Nhẫn lửa), các sợi dây chuyền Pendant of Ice (Dây chuyền băng) v.v... khi + lvl của các món này càng cao, thì kháng hiệu ứng của chúng sẽ được tăng lên, ví dụ 1 con elf bắn băng, nếu bạn sử dụng cái ring of ice + 4 vậy xem như elf bắn bạn rất ít dính băng.
>
> Chẳng những như vậy, ở tất cả chỉ số của quái, boss, đều có kháng, nếu bạn nào từng nghịch lung tung 1 vài file config của server, sẽ thấy chúng đều có kháng các loại thuộc tính, nguyên tố (element). Nên có 1 số sv lậu , khi các bạn chơi dw đánh poison vào boss, máu rút theo 10% máu của boss. Sv mu0rs.com, khi xưa cũng từng dính vụ này. Sau này, Tân chỉnh cho mấy con boss kháng độc max 255/255, nên ko còn bị nữa.
> 
> Ngoài ra, ở các món đồ mang trên người của nhân vật, chúng cũng có kháng các thuộc tính, cũng như các loại vũ khí cũng có các loại thuộc tính riêng. Rồi ở giầy thì có chỉ số di chuyển nhanh , ở tay thì có tốc độ đánh nhanh, ở wings thì có + % di chuyển , bay nhanh hơn, tùy thuộc vào từng món mà có giá trị cụ thể khác nhau.
> 
> Nhưng.. Webzen đã ko làm tròn hết, có lẽ khi xưa, webzen đã từng muốn phát triển theo như thế, nhưng sau này, lý do vì sao thì Tân ko biết, họ ngưng phát triển theo hướng này. Cho nên có 1 số thuộc tính họ để sẳn đó, nhưng chưa từng đụng đến.
> 
> Và rồi , 1 ngày đẹp trời... Tân và Gouken tâm đầu ý hợp, bàn bạc viết cái element này tiếp theo ... "dùm webzen" (bố láo 1 xíu ^^!). Thế là tính năng element ra đời. Cũng như cũ, cũng dựa trên 1 số thông số có sẳn của webzen còn bỏ dang dở ra mà viết tiếp, cũng là các băng, lửa, điện, độc..... Hiện nay, tính năng đã hoàn thành, đã đem vào dùng cho server từ mấy năm rồi. Nhưng ko có 1 hướng dẫn chi tiết, rõ ràng cụ thể nào cho 1 số anh em chân ướt , chân ráo tìm hiểu cũng như định hướng build.
>
> Tôi khẳng định, đây là 1 tính năng custom hay và độc quyền của server mu0rs.com. Chúng tôi viết và dựa trên cái có sẳn mà webzen để lại, chúng tôi thừa hưởng nó từ đàn anh webzen để viết ra, chứ ko phải tự sáng chế ra 100%. Ngoài ra, còn ăn cắp thêm 1 số ý tưởng từ game tôi yêu thích PoE (path of exile). Tuy nhiên.... có 1 số thứ vẫn chưa hoạt động đúng, hoạt động lỗi, hoặc quá mạnh, quá yếu so với quy định. Và trong quá trình phát triển của Mu0rs.com, sẽ có cập nhật, thay đổi, chỉnh sửa, nhằm giúp cho cân bằng hơn, balance hơn (nói về balance, sv clbmu,mu0rs gần như config khá tốt, chấp nhận được, ko hoàn hảo nhưng đở hơn các sv của anh em khác). Và những lần chỉnh sửa này, ảnh hưởng ít nhiều đến cách build, cách lên đồ của các bạn.....Cái này, thật sự rất khó nói, vì trước khi ra tính năng này, chúng tôi đã từng nói, nó sẽ ko ổn định, thậm chí rất khó để cân balance... Nên sẽ có các cập nhật thay đổi phù hợp theo từng giai đoạn phát triển của server v.v.... Việc này, sẽ làm mất lòng , mất tiền, mất time của 1 số anh em. Mong anh em chấp nhận cùng chúng tôi. Ai mà muốn đi chỉnh tới chỉnh lui hoài cơ chứ... Nhưng nó quá bá hoặc quá yếu thì phải tăng giảm ....

# Thuộc Tính
| Element | Mô Tả | Số lượng tính năng (opt) | Hiệu ứng | Tác dụng đặc biệt | Ví dụ tham khảo |
|:--------|:------|:------------------------|:---------|:------------------|:------|
| [Fire](/elements/fire) | Nguyên tố lửa | 0 | ![ele-fire-spec.gif](/assets/elements/ele-fire-spec.gif) | - `Đốt cháy` đối phương.<br>- Gây sát thương đốt máu liên tục. Sát thương đốt cháy dựa vào sát thương gây ra cuối cùng của đòn đánh (kỹ năng).<br>- Giảm giáp đối phương. | Phù hợp kiểu build có dame kết thúc lớn. 
| [Ice](/elements/ice) | Nguyên tố băng | 0 | ![ele-ice-spec.gif](/assets/elements/ele-ice-spec.gif) | - `Đóng băng` đối phương `0.5s` sau đó `làm chậm` trong `7s`. <br>- Khi bị `đóng băng` giảm `100%` khả năng `né tránh` và `100%` khả năng `block` đòn đánh của đối phương.<br>- Sát thương bị gây khi đối phương trong trạng thái `làm chậm`, sẽ tăng thêm `50%` tỉ lệ xuất hiện sát thương hoàn hảo. | Phù hợp với các build gây sát thương liên tục thật nhanh, hoặc cần phá block ( đỡ đòn từ khiên ), phá né của đối phương |
| [Lighting](/elements/lighting) | Nguyên tố sét | 0 | ![ele-lighting-spec.gif](/assets/elements/ele-lighting-spec.gif) | - `Choáng` đối phương trong `1s`.<br> - Khi bị `choáng` giảm `100%` khả năng `né tránh` và `100%` khả năng `block` đòn đánh của đối phương.<br>- Trong 5s hưởng hiệu ứng `30%` bỏ qua phòng thủ đối phương.<br>- Khi đối phương bị `crit dmg` từ nguyên tố này, sẽ bị knock back (đẩy lùi) 2-3 ô gì đó | Phù hợp với build có số hit đánh ra nhanh và nhiều |
| [Posion](/elements/posion) | Nguyên tố độc | 0 | ![ele-posion-spec.gif](/assets/elements/ele-posion-spec.gif) | - `Dính độc`, rút máu.<br>- Giảm né của đối phương 30%. <br>- Giảm hồi máu đối phương 50% (giống hiệu ứng `Vết Thương Sâu` của LOL hay hiệu ứng của `Eye of Skadi` bên DotA 2  | Phù hợp khi đối đầu với đối thủ nhiều máu. |

# Trang bị có thể nâng cấp

- Đồ thường
- Đồ exc
- Đồ 380
- Đồ thần

# Cách các thuộc tính hoạt động

Mỗi trang bị có thể có 2 `opt thuộc tính` và 1 `opt đặc biệt`.

## Opt thuộc tính (E1,E2)

Mình sẽ chia làm 2 loại: `Công` và `Thủ`

- opt `công` (<span class="mdi mdi-sword"></span>) gây sát thương thuộc tinh / giảm thủ thuộc tính đôi phương và hiệu ứng thuộc tinh.
- opt `thủ` (<span class="mdi mdi-shield"></span>) giảm / kháng / né sát thương thuộc tinh và hiệu ứng thuộc tinh.

Tổng hợp nhanh sẽ có những opt [E1, E2](#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2) như sau (`/` nghĩa là hoặc): 

| Opt thuộc tinh | Loại | Min X/Y | Max X/Y | Mũ | Áo | Quần | Tay | Chân | Nhẫn | Vòng Cổ | Vũ Khí | Khiên |
|:---------------|:----:|:-------:|:-------:|:--:|:--:|:----:|:---:|:----:|:----:|:-------:|:------:|:-----:|
| Add `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element damage `x` - `y` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element special rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element damage `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element critical rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element double rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element ignore rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element effect time `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Decrease target `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element defense `x` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Decrease target `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element absorb `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Add `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` defense `x` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Absorb `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element damage `x%` | <span class="mdi mdi-shield"/> |  <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element defense `x%` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Resist `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element effect `x%` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Absorb `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element damage to HP `x%` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Max Resist `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element `x%` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Max Dodge `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element damage `x%` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Decrease `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` effect time `x%` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Dodge `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element damage `x%` | <span class="mdi mdi-shield"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |

>Các op `ALL element` mặc định sẽ là `FIRE`.
{.is-info}

> Opt "Dodge `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element damage`x%`" => được giới hạn max 80%. Nhiều hơn cũng chỉ tính 80%
{.is-info}

> Opt "Increase `FIRE` / `ICE` / `LIGHTING` / `POSION` / `ALL` element special rate `x%` => được giới hạn max 15%.
{.is-info}

> Nếu có hơn 1 opt nguyên tố, thì sẽ tính theo opt nguyên tố nào có giá trị cao nhất.
{.is-info}

## Opt đặc biệt (E3)

Mình sẽ chia làm 3 loại: `Công` (<span class="mdi mdi-sword"/>), `Thủ` (<span class="mdi mdi-shield"/>) và `Hỗ Trợ` (<span class="mdi mdi-shield-cross-outline"/>)

- opt `Công` (<span class="mdi mdi-sword"/>) gây sát thương, hiệu ứng, giảm giáp / block / SD, bỏ qua SD..vv
- opt `Thủ` (<span class="mdi mdi-shield"/>) giảm sát thương, hiệu ứng. Tăng giáp, khả năng block..vv
- opt `Hỗ Trợ` (<span class="mdi mdi-shield-cross-outline"/>) tăng điểm stat, HP, MP, AG, SD. Khả năng hồi phục...vv 

Tổng hợp nhanh sẽ có những opt [E3](#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3) như sau (`/` nghĩa là hoặc):

| Opt thuộc tinh | Loại | Min X/Y | Max X/Y | Mũ | Áo | Quần | Tay | Chân | Nhẫn | Vòng Cổ | Vũ Khí | Khiên |
|:---------------|:----:|:-------:|:-------:|:--:|:--:|:----:|:---:|:----:|:----:|:-------:|:------:|:-----:|
| Add `Strength` / `Dexterity` / `Vitality` / `Energy` / `LeadherShip` / `all Stat` + `x` point | <span class="mdi mdi-shield-cross-outline"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | |
| Add `SD` / `Mana` / `HP` `x` | <span class="mdi mdi-shield-cross-outline"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | |
| Increase `Strength` / `Dexterity` / `Vitality` / `Energy` / `LeadherShip` / `All Stat` + `x%` | <span class="mdi mdi-shield-cross-outline"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Add AG `x` | <span class="mdi mdi-shield-cross-outline"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | |
| Increase `SD` / `Mana` / `HP` / `Regen SD` / `Regen Mana` / `Regen HP` `x%` | <span class="mdi mdi-shield-cross-outline"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Increase AG `x`% | <span class="mdi mdi-shield-cross-outline"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `Defense` / ` Defense Rate PvP` `x%` | <span class="mdi mdi-shield"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Increase Defense Rate `x` | <span class="mdi mdi-shield"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Increase `Def` / `Def Rate` with Shield `x%` | <span class="mdi mdi-shield"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Add Def with `Shield` / `Shield PvP` `x` | <span class="mdi mdi-shield"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Add Def Rate with Shield `x` | <span class="mdi mdi-shield"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Add `Defense` / `PvP Defense` | <span class="mdi mdi-shield"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Add `Reflect` / `Resist Reflect` / `Resist Stun` / `Resist Ice` / `Resist Poison` / `Resist Sleep` `x%` | <span class="mdi mdi-shield"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> |
| Add `physical` / `spell` / `curserd` / `skill` damage `x` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Add attack `rating` / `rating PvP` + `x` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Add `Critical` / `Excellent` / `Ignore` / `Double` damage Rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Add `Decrease` / `Ignore Decrease` SD Rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Add `Interrupt` / `Stun` / `Bleeding` Rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `physical` / `magical` / `cursed` damge %.2f%%%% | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase attack `rating` / `rating Pvp` `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase damage with `Sword(Claw)` / `Axe` / `Mace(Scepter)` / `Spear` / `Bow` / `Xbow` `x` (dmg) / `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `Spell` / `Cursed` damage with `Staff` / `Book` + `x` (dmg) / `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `Critical` / `Excellent` / `Ignore` / `Double` damage `x` (dmg) / `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Increase `Bypass SD` Rate `x`% | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Decrease target Defense `x` / `x`% | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Decrease `damage Reduction` / `Shield Block` Rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Reflect dmg chance stun when horse riding `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Raven `Double` / `Ignore` damage Rate `x%` | <span class="mdi mdi-sword"/> | | | | | | <span class="mdi mdi-check"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | |
| Reduce `Critical` / `Excellent` / `Ignore` / `Double`  Dmg Rate `x%` | <span class="mdi mdi-sword"/> | | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | <span class="mdi mdi-check"/> | <span class="mdi mdi-check"/> | | | |
| Reduce Dmg From `DW` / `DK` / `ELF` / `MG` / `DL` / `SM` / `RF` `x%` | <span class="mdi mdi-sword"/> | | | | | | | | <span class="mdi mdi-check"/> | | | |
| Add Shield Block Rate `x%` | <span class="mdi mdi-sword"/> | | | | | | | | | | | <span class="mdi mdi-check"/> |
| Add Resist Bypass SD  `x%` | <span class="mdi mdi-sword"/> | | | | | | | | | | | <span class="mdi mdi-check"/> |
| Mana Shield `x%` | <span class="mdi mdi-sword"/> | | | | | | | | | | | <span class="mdi mdi-check"/> |
| Opt thuộc tinh | Loại | Min X/Y | Max X/Y | Mũ | Áo | Quần | Tay | Chân | Nhẫn | Vòng Cổ | Vũ Khí | Khiên |

## Opt đặc biệt chỉ có trên Cánh (Wings)

Tổng hợp nhanh sẽ có những opt như sau (`/` nghĩa là hoặc):

| Opt thuộc tinh | Loại | Min x | Max x|
|:---------------|:----:|:------|:-----|
| Hut `mau` / `mana` theo  `x%` dmg | <span class="mdi mdi-shield-cross-outline"/> | - | - |
| Hoi phuc full SD khi tan cong `x%` | <span class="mdi mdi-shield"/>  | - | - |
| Tang `x%` co hoi ra `x2` / `ign def` | <span class="mdi mdi-sword"/> | - | - |
| Tang them `x%` khi dung Dai Quy(Soi Tinh) | <span class="mdi mdi-sword"/> | - | - |
| `x%` Tang 20% dmg trong 5s | <span class="mdi mdi-sword"/> | - | - |
| `x%` Xuat hien MNL 20% trong 5s | <span class="mdi mdi-sword"/> | - | - |
| Giam `x%` `HP` / `DEF` de tang 20% dmg | <span class="mdi mdi-sword"/> | - | - |
| Giam`x%` de tang 20% dmg | <span class="mdi mdi-sword"/> | - | - |
| Tang `x%` kha nang roi do Exc | <span class="mdi mdi-shield-cross-outline"/> | - | - |
| Tang `x%` kha nang roi do Than | <span class="mdi mdi-shield-cross-outline"/> | - | - |
| Tang `x%` kha nang rot do ngon | <span class="mdi mdi-shield-cross-outline"/> | - | - |
| Minions damage rate `x%` | <span class="mdi mdi-sword"/> | - | - |
| LSD `x%` | <span class="mdi mdi-sword"/> | - | - |
| Co `x%`  pha het `MANA` / `AG` doi phuong | <span class="mdi mdi-sword"/> | - | - |
| Co `x%` tang 30%% final dmg 8s khi mau duoi 60% | <span class="mdi mdi-sword"/> | - | - |
| Co`x%` danh ko miss trong 5s | <span class="mdi mdi-sword"/> | - | - |
| Tang `x%` `STR` / `DEX` / `VIT` / `ENE` / `CMD` | <span class="mdi mdi-sword"/> | - | - |
| Co `x%` giam 50%% chinh xac ke dich 5s | <span class="mdi mdi-sword"/> | - | - |
| Co `x%` khoa skill ke dich trong 3s | <span class="mdi mdi-sword"/> | - | - |
| Co `x%` giam toc do cua ke dich 3s | <span class="mdi mdi-sword"/> | - | - |
| Co`x%` bien char khac thanh tho 3s | <span class="mdi mdi-sword"/> | - | - |
| Co `x%` supper ign | <span class="mdi mdi-sword"/> | - | - |
| Dam gio gay stun `x%` | <span class="mdi mdi-sword"/> | - | - |
| Combo DK pha het SD `x%` | <span class="mdi mdi-sword"/> | - | - |
| Mui ten bang xuyen khang bang `x%` | <span class="mdi mdi-sword"/> | - | - |
| XTT xuyen giap `x%` | <span class="mdi mdi-sword"/> | - | - |
| Ngu tien gay stun va knocback `x%` | <span class="mdi mdi-sword"/> | - | - |
| Tang effect buff def `x%` | <span class="mdi mdi-shield"/> | - | - |
| Tang effect buff attack `x%` | <span class="mdi mdi-sword"/> | - | - |
| EletricSpike tang dmg va ign rate dua theo STR / `x` | <span class="mdi mdi-sword"/> | - | - |
| Giam dat giam delay 5s va stun `x%` | <span class="mdi mdi-sword"/> | - | - |
| Khi Tele co `x%` mien sat thuong cua qua tinh | <span class="mdi mdi-shield"/> | - | - |
| Nova duoc bonus tu ENE `x%` | <span class="mdi mdi-sword"/> | - | - |
| Decay xuyen khang doc `x%` | <span class="mdi mdi-sword"/> | - | - |
| Hoi tho rong huy SD,AG,Mana theo ENE / `x` | <span class="mdi mdi-sword"/> | - | - |
| Gam thet hut SD theo `x%` dmg | <span class="mdi mdi-sword"/> | - | - |
| Chem lua tru giap cong them va xuyen khang lua `x%` | <span class="mdi mdi-sword"/> | - | - |
| Berserker giam tru HP,DEF,AG va tang DMG `x%` | <span class="mdi mdi-sword"/> | - | - |
| Drain Life hut SD `x%` cua so mau hut dc | <span class="mdi mdi-sword"/> | - | - |
| Gigantic Storm gay stun va xuat hien ign dmg theo ENE / `x` | <span class="mdi mdi-sword"/> | - | - |

# Ngọc Thuộc Tính
| Tên | Mô Tả | Công Dụng | Sử dụng cho | Nguồn |
|:----|:------:|:---------|:------------|:----|
| Jewel of Transmutation | ![](/assets/jewels/jewel-of-transmutation.gif) | - Đập vào đồ để tạo opt thuộc tính nguyên tô.<br>- Mặc định sẽ xuât hiện thuộc tinh [E1](#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2). Ngoài ra có xác suất xuất hiện thêm opt thuộc tính [E2](#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2), [E3](#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3)<br>- Không sử dụng được cho trang bị đã có [E3](#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3) | - [Mũ]().<br>- [Áo]().<br>- [Quần]().<br>- [Găng Tay]().<br>- [Giày]().<br>- [Nhẫn]().<br>- [Vòng cổ](). | Đánh quái rớt |
| Jewel of Alteration | ![](/assets/jewels/jewel-of-alteration.gif) | - Dùng để đổi ngẫu nhiên các opt thuộc tinh [E1, E2](#opt-thu%E1%BB%99c-t%C3%ADnh-e1e2).<br>- Không sử dụng được cho trang bị đã có [E3](#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3) | Như Trên | Đánh quái rớt |
| Jewel of Augmentation | ![](/assets/jewels/jewel-of-augmentation.gif) | - Tăng thêm 1 opt thuộc tính.<br>- Không sử dụng được cho trang bị đã có [E3](#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3) | Như Trên | Đánh quái rớt |
| Jewel of Divine | ![](/assets/jewels/jewel-of-divine.gif) | Thay đổi ngẫu nhiên giá trị của các opt thuộc tính. | Như Trên | Đánh quái rớt |
| Jewel of Scouring | ![](/assets/jewels/jewel-of-scouring.gif) | Xóa tất cả opt thuộc tính. | Như Trên | Đánh quái rớt |
| Jewel of Annulment | ![](/assets/jewels/jewel-of-annulment.png) | Xóa ngẫu nhiên 1 trong 3 opt thuộc tính [[E1](/elements/), [E2](), [E3](#opt-%C4%91%E1%BA%B7c-bi%E1%BB%87t-e3)] | Như Trên | [Ghép](/craft/jewel-of-annulment) |
| Jewel of Exalted | ![](/assets/jewels/jewel-of-exalted.gif) | [Nâng cấp](/craft/ele-wings) opt thuộc tính cho [Cánh](/items/wings) | [Cánh](/items/wings) | [Ghép](/craft/jewel-of-exalted) |

# Liên quan

- [Fire Element](/vi/elements/fire)
- [Fire Ice](/vi/elements/ice)
- [Fire Lighting](/vi/elements/lighting)
- [Fire Posion](/vi/elements/posion)
- [Nén Ngọc Thuộc Tính](/vi/commands/zip-jewel-of-elements)
{.links-list}