---
title: Elements
description: 
published: true
date: 2024-11-10T07:25:46.681Z
tags: ele, posion, lighting, fire, ice, element
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
| [Posion](/elements/posion) | Nguyên tố độc | 0 | ![ele-posion-spec.gif](/assets/elements/ele-posion-spec.gif) | - Dính `độc`, rút máu.<br>- Giảm né của đối phương 30%. <br>- Giảm hồi máu đối phương 50% (giống hiệu ứng `Vết Thương Sâu` của LOL hay hiệu ứng của `Eye of Skadi` bên DotA 2  | Phù hợp khi đối đầu với đối thủ nhiều máu. |


# Trang bị có thể nâng cấp

- Đồ thường
- Đồ exc
- Đồ 380
- Đồ thần

# Cách các thuộc tính hoạt động

Mỗi trang bị có thể có 2 `opt thuộc tính` và 1 `opt đặc biệt`.

## Opt thuộc tính (E1,E2)

Mình sẽ chia làm 2 loại: `Công` và `Thủ`

Những opt `công` (<span class="mdi mdi-sword"></span>) gây sát thương thuộc tinh / giảm thủ thuộc tính đôi phương và hiệu ứng thuộc tinh.
Những opt `thủ` (<span class="mdi mdi-shield"></span>) giảm / kháng / né sát thương thuộc tinh và hiệu ứng thuộc tinh.

Ví du: Với `X-ELE` bao gồm cái thuôc tính: `FIRE`, `ICE`, `LIGHTING`, `POSION`.

| Opt thuộc tinh | Loại | Min X/Y | Max X/Y |
|:---------------|:-----:|:----|:----|
| Add `X-ELE` element damage `X - Y` | <span class="mdi mdi-sword"></span> | 1 - 2 | 45 - 60 |
| Increase `X-ELE` element damage `X`% | <span class="mdi mdi-sword"></span> | 3% | 15% |
| Decrease target `X-ELE` element defense `X` | <span class="mdi mdi-sword"></span> | 10 | 50 |
| Decrease target FIRE element absorb `X`% | <span class="mdi mdi-sword"></span> | | |
| Increase `X-ELE` element critical rate `X`% | <span class="mdi mdi-sword"></span> | 5% | 15% |
| Increase `X-ELE` element double rate `X`% | <span class="mdi mdi-sword"></span> | | |
| Increase `X_ELE` element ignore rate `X`% | <span class="mdi mdi-sword"></span> | | |
| Increase `X_ELE` element effect time `X`% | <span class="mdi mdi-sword"></span> | | |
| Increase `X_ELE` element special rate `X`% | <span class="mdi mdi-sword"></span> | | |
| Add `X_ELE` defense `X` | <span class="mdi mdi-shield"></span> | | |
| Absorb `X_ELE` element damage `X`% | <span class="mdi mdi-shield"></span> | | |
| Increase `X_ELE` element defense `X`% | <span class="mdi mdi-shield"></span> | | |
| Resist `X_ELE` element effect `X`% | <span class="mdi mdi-shield"></span> | | |
| Absorb `X_ELE` element damage to HP `X`% | <span class="mdi mdi-shield"></span> | | |
| Max Resist `X_ELE` element `X`% | <span class="mdi mdi-shield"></span> | | |
| Max Dodge `X_ELE` element damage `X`% | <span class="mdi mdi-shield"></span> | | | 
| Decrease `X_ELE` effect time `X`% | <span class="mdi mdi-shield"></span> | | |
| Dodge `X_ELE` element damage` X`% | <span class="mdi mdi-shield"></span> | | |

## Opt đặc biệt (E3)

Một món đồ có max là 2 opt ele (E1, E2) và 1 opt đặc biệt (E3).
E1-E2 là các opt có khả năng gây ra dmg và hiệu ứng thuộc tính
E3 là các opt đặc biệt tăng các chỉ số cho nhân vật như tăng dmg, tăng x2, tăng exc rate v.v... trên các trang bị vũ khí, tay, dây chuyền và các chỉ số như tăng giáp, tăng máu, tăng né, giảm lsd, block v.v.... trên giáp trụ , nhẫn, khiên.
Các opt ele được sử dụng trên các loại đồ nào ?

Riêng các loại giáp trụ socket thì ko có ele. Nhưng vũ khí socket thì có ele ẩn theo từng vũ khí. Ngoài ra 1 số vũ khí rồng cũng có ele ẩn, khi cầm lên đã có sẳn ele. Nếu đập ele thêm trên các vk này, thì ele đập vào sẽ được + dồn nếu cùng loại, còn nếu khác loại sẽ tính và lấy theo giá trị cao của loại có giá trị cao hơn.

# Ngọc Thuộc Tính
| Tên | Mô Tả | Công Dụng | Sử dụng cho | Nguồn |
|:----|:------|:---------|:------------|:----|
| Jewel of Transmutation | ![](/assets/jewels/jewel-of-transmutation.gif) | - Đập vào đồ để tạo opt thuộc tính nguyên tô.<br>- Mặc định sẽ xuât hiện thuộc tinh [E1](). Ngoài ra có xác suất xuất hiện thêm opt thuộc tính [E2](), [E3]()<br>- Không sử dụng được cho trang bị đã có [E3]() | - [Mũ]().<br>- [Áo]().<br>- [Quần]().<br>- [Găng Tay]().<br>- [Giày]().<br>- [Nhẫn]().<br>- [Vòng cổ](). | Đánh quái rớt |
| Jewel of Alteration | ![](/assets/jewels/jewel-of-alteration.gif) | - Dùng để đổi ngẫu nhiên các opt thuộc tinh [E1](), [E2]().<br>- Không sử dụng được cho trang bị đã có [E3]() | Như Trên | Đánh quái rớt |
| Jewel of Augmentation | ![](/assets/jewels/jewel-of-augmentation.gif) | - Tăng thêm 1 opt thuộc tính.<br>- Không sử dụng được cho trang bị đã có [E3]() | Như Trên | Đánh quái rớt |
| Jewel of Divine | ![](/assets/jewels/jewel-of-divine.gif) | Thay đổi ngẫu nhiên giá trị của các opt thuộc tính. | Như Trên | Đánh quái rớt |
| Jewel of Scouring | ![](/assets/jewels/jewel-of-scouring.gif) | Xóa tất cả opt thuộc tính. | Như Trên | Đánh quái rớt |
| Jewel of Annulment | ![](/assets/jewels/jewel-of-annulment.gif) | Xóa ngẫu nhiên 1 trong 3 opt thuộc tính [[E1](), [E2](), [E3]()] | Như Trên | [Ghép](/craft/jewel-of-annulment) |
| Jewel of Exalted | ![](/assets/jewels/jewel-of-exalted.gif) | [Nâng cấp](/craft/ele-wings) opt thuộc tính cho [Cánh]() | [Cánh]() | [Ghép](/craft/jewel-of-exalted) |