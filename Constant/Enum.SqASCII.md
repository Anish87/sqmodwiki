# Introduction

Identifies ASCII characters.

# Specifications

```D
enum SqWep
```

----

| Name | Type | Description |
|---|---|---|
| **Unknown** | `integer` | Unknown changed occurred. Never really used but added for consistency |
| **Nul** | `integer` | Alias of ASCII character identifier: `0` |
| **Soh** | `integer` | Alias of ASCII character identifier: `1` |
| **Stx** | `integer` | Alias of ASCII character identifier: `2` |
| **Etx** | `integer` | Alias of ASCII character identifier: `3` |
| **Eot** | `integer` | Alias of ASCII character identifier: `4` |
| **Enq** | `integer` | Alias of ASCII character identifier: `5` |
| **Ack** | `integer` | Alias of ASCII character identifier: `6` |
| **Bel** | `integer` | Alias of ASCII character identifier: `7` |
| **Bs** | `integer` | Alias of ASCII character identifier: `8` |
| **Tab** | `integer` | Alias of ASCII character identifier: `9` |
| **Lf** | `integer` | Alias of ASCII character identifier: `10` |
| **Vt** | `integer` | Alias of ASCII character identifier: `11` |
| **Ff** | `integer` | Alias of ASCII character identifier: `12` |
| **Cr** | `integer` | Alias of ASCII character identifier: `13` |
| **So** | `integer` | Alias of ASCII character identifier: `14` |
| **Si** | `integer` | Alias of ASCII character identifier: `15` |
| **Dle** | `integer` | Alias of ASCII character identifier: `16` |
| **Dc1** | `integer` | Alias of ASCII character identifier: `17` |
| **Dc2** | `integer` | Alias of ASCII character identifier: `18` |
| **Dc3** | `integer` | Alias of ASCII character identifier: `19` |
| **Dc4** | `integer` | Alias of ASCII character identifier: `20` |
| **Nak** | `integer` | Alias of ASCII character identifier: `21` |
| **Syn** | `integer` | Alias of ASCII character identifier: `22` |
| **Etb** | `integer` | Alias of ASCII character identifier: `23` |
| **Can** | `integer` | Alias of ASCII character identifier: `24` |
| **Em** | `integer` | Alias of ASCII character identifier: `25` |
| **Sub** | `integer` | Alias of ASCII character identifier: `26` |
| **Esc** | `integer` | Alias of ASCII character identifier: `27` |
| **Fs** | `integer` | Alias of ASCII character identifier: `28` |
| **Gs** | `integer` | Alias of ASCII character identifier: `29` |
| **Rs** | `integer` | Alias of ASCII character identifier: `30` |
| **Us** | `integer` | Alias of ASCII character identifier: `31` |
| **Space** | `integer` | Alias of ASCII character identifier: `32` |
| **Exclamation_point** | `integer` | Alias of ASCII character identifier: `33` |
| **Double_quotes** | `integer` | Alias of ASCII character identifier: `34` |
| **Number_sign** | `integer` | Alias of ASCII character identifier: `35` |
| **Dollar_sign** | `integer` | Alias of ASCII character identifier: `36` |
| **Percent_sign** | `integer` | Alias of ASCII character identifier: `37` |
| **Ampersand** | `integer` | Alias of ASCII character identifier: `38` |
| **Single_quote** | `integer` | Alias of ASCII character identifier: `39` |
| **Opening_parenthesis** | `integer` | Alias of ASCII character identifier: `40` |
| **Closing_parenthesis** | `integer` | Alias of ASCII character identifier: `41` |
| **Asterisk** | `integer` | Alias of ASCII character identifier: `42` |
| **Plus** | `integer` | Alias of ASCII character identifier: `43` |
| **Comma** | `integer` | Alias of ASCII character identifier: `44` |
| **Minus** | `integer` | Alias of ASCII character identifier: `45` |
| **Period** | `integer` | Alias of ASCII character identifier: `46` |
| **Slash** | `integer` | Alias of ASCII character identifier: `47` |
| **Zero** | `integer` | Alias of ASCII character identifier: `48` |
| **One** | `integer` | Alias of ASCII character identifier: `49` |
| **Two** | `integer` | Alias of ASCII character identifier: `50` |
| **Three** | `integer` | Alias of ASCII character identifier: `51` |
| **Four** | `integer` | Alias of ASCII character identifier: `52` |
| **Five** | `integer` | Alias of ASCII character identifier: `53` |
| **Six** | `integer` | Alias of ASCII character identifier: `54` |
| **Seven** | `integer` | Alias of ASCII character identifier: `55` |
| **Eight** | `integer` | Alias of ASCII character identifier: `56` |
| **Nine** | `integer` | Alias of ASCII character identifier: `57` |
| **Colon** | `integer` | Alias of ASCII character identifier: `58` |
| **Emicolon** | `integer` | Alias of ASCII character identifier: `59` |
| **Less_than_sign** | `integer` | Alias of ASCII character identifier: `60` |
| **Equal_sign** | `integer` | Alias of ASCII character identifier: `61` |
| **Greater_than_sign** | `integer` | Alias of ASCII character identifier: `62` |
| **Question_mark** | `integer` | Alias of ASCII character identifier: `63` |
| **At** | `integer` | Alias of ASCII character identifier: `64` |
| **Upper_a** | `integer` | Alias of ASCII character identifier: `65` |
| **Upper_b** | `integer` | Alias of ASCII character identifier: `66` |
| **Upper_c** | `integer` | Alias of ASCII character identifier: `67` |
| **Upper_d** | `integer` | Alias of ASCII character identifier: `68` |
| **Upper_e** | `integer` | Alias of ASCII character identifier: `69` |
| **Upper_f** | `integer` | Alias of ASCII character identifier: `70` |
| **Upper_g** | `integer` | Alias of ASCII character identifier: `71` |
| **Upper_h** | `integer` | Alias of ASCII character identifier: `72` |
| **Upper_i** | `integer` | Alias of ASCII character identifier: `73` |
| **Upper_j** | `integer` | Alias of ASCII character identifier: `74` |
| **Upper_k** | `integer` | Alias of ASCII character identifier: `75` |
| **Upper_l** | `integer` | Alias of ASCII character identifier: `76` |
| **Upper_m** | `integer` | Alias of ASCII character identifier: `77` |
| **Upper_n** | `integer` | Alias of ASCII character identifier: `78` |
| **Upper_o** | `integer` | Alias of ASCII character identifier: `79` |
| **Upper_p** | `integer` | Alias of ASCII character identifier: `80` |
| **Upper_q** | `integer` | Alias of ASCII character identifier: `81` |
| **Upper_r** | `integer` | Alias of ASCII character identifier: `82` |
| **Upper_s** | `integer` | Alias of ASCII character identifier: `83` |
| **Upper_t** | `integer` | Alias of ASCII character identifier: `84` |
| **Upper_u** | `integer` | Alias of ASCII character identifier: `85` |
| **Upper_v** | `integer` | Alias of ASCII character identifier: `86` |
| **Upper_w** | `integer` | Alias of ASCII character identifier: `87` |
| **Upper_x** | `integer` | Alias of ASCII character identifier: `88` |
| **Upper_y** | `integer` | Alias of ASCII character identifier: `89` |
| **Upper_z** | `integer` | Alias of ASCII character identifier: `90` |
| **Opening_bracket** | `integer` | Alias of ASCII character identifier: `91` |
| **Backslash** | `integer` | Alias of ASCII character identifier: `92` |
| **Closing_bracket** | `integer` | Alias of ASCII character identifier: `93` |
| **Caret** | `integer` | Alias of ASCII character identifier: `94` |
| **Underscore** | `integer` | Alias of ASCII character identifier: `95` |
| **Grave_accent** | `integer` | Alias of ASCII character identifier: `96` |
| **Lower_a** | `integer` | Alias of ASCII character identifier: `97` |
| **Lower_b** | `integer` | Alias of ASCII character identifier: `98` |
| **Lower_c** | `integer` | Alias of ASCII character identifier: `99` |
| **Lower_d** | `integer` | Alias of ASCII character identifier: `100` |
| **Lower_e** | `integer` | Alias of ASCII character identifier: `101` |
| **Lower_f** | `integer` | Alias of ASCII character identifier: `102` |
| **Lower_g** | `integer` | Alias of ASCII character identifier: `103` |
| **Lower_h** | `integer` | Alias of ASCII character identifier: `104` |
| **Lower_i** | `integer` | Alias of ASCII character identifier: `105` |
| **Lower_j** | `integer` | Alias of ASCII character identifier: `106` |
| **Lower_k** | `integer` | Alias of ASCII character identifier: `107` |
| **Lower_l** | `integer` | Alias of ASCII character identifier: `108` |
| **Lower_m** | `integer` | Alias of ASCII character identifier: `109` |
| **Lower_n** | `integer` | Alias of ASCII character identifier: `110` |
| **Lower_o** | `integer` | Alias of ASCII character identifier: `111` |
| **Lower_p** | `integer` | Alias of ASCII character identifier: `112` |
| **Lower_q** | `integer` | Alias of ASCII character identifier: `113` |
| **Lower_r** | `integer` | Alias of ASCII character identifier: `114` |
| **Lower_s** | `integer` | Alias of ASCII character identifier: `115` |
| **Lower_t** | `integer` | Alias of ASCII character identifier: `116` |
| **Lower_u** | `integer` | Alias of ASCII character identifier: `117` |
| **Lower_v** | `integer` | Alias of ASCII character identifier: `118` |
| **Lower_w** | `integer` | Alias of ASCII character identifier: `119` |
| **Lower_x** | `integer` | Alias of ASCII character identifier: `120` |
| **Lower_y** | `integer` | Alias of ASCII character identifier: `121` |
| **Lower_z** | `integer` | Alias of ASCII character identifier: `122` |
| **Opening_brace** | `integer` | Alias of ASCII character identifier: `123` |
| **Vertical_bar** | `integer` | Alias of ASCII character identifier: `124` |
| **Closing_brace** | `integer` | Alias of ASCII character identifier: `125` |
| **Tilde** | `integer` | Alias of ASCII character identifier: `126` |
| **Undefined** | `integer` | Alias of ASCII character identifier: `127` |
| **Max** | `integer` | Maximum identifier in this enumeration |
