# Binary-Search-Tree-Projesi
Patika dev profilim için [tıklayınız.](https://app.patika.dev/ailker)

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamaları;
<table width="27%" border="1" cellpadding="0" cellspacing="0">

<tbody>

<tr>

<td></td>

<td></td>

<td></td>

<td>  </td>

<td>  </td>

<td>  </td>

<td>7</td>

<td>  </td>

<td>  </td>

<td>  </td>

<td>  </td>

</tr>

<tr>

<td></td>

<td></td>

<td></td>

<td></td>

<td></td>

<td>/</td>

<td></td>

<td>\</td>

<td></td>

<td></td>

<td></td>

</tr>

<tr>

<td></td>

<td></td>

<td></td>

<td></td>

<td>5</td>

<td></td>

<td></td>

<td></td>

<td>8</td>

<td></td>

<td></td>

</tr>

<td></td>

<td></td>

<td></td>

<td>/</td>

<td></td>

<td>\</td>

<td></td>

<td></td>

<td></td>

<td>\</td>

<td></td>

<tr>

<td></td>

<td></td>

<td>1</td>

<td></td>

<td></td>

<td></td>

<td>6</td>

<td></td>

<td></td>

<td></td>

<td>9</td>

</tr>

<tr>

<td></td>

<td>/</td>

<td></td>

<td>\</td>

<td></td>

<td></td>

<td></td>

<td></td>

<td></td>

<td></td>

<td></td>

</tr>

<tr>

<td>0</td>

<td></td>

<td></td>

<td></td>

<td>3</td>

<td></td>

<td></td>

<td></td>

<td></td>

<td></td>

<td></td>

</tr>

<tr>

<td></td>

<td></td>

<td></td>

<td>/</td>

<td></td>

<td>\</td>

<td></td>

<td></td>

<td></td>

<td></td>

<td></td>

</tr>

<tr>

<td></td>

<td></td>

<td>2</td>

<td></td>

<td></td>

<td></td>

<td>4</td>

<td></td>

<td></td>

<td></td>

<td></td>

</tr>

</tbody>

</table>

### Aşamaları;
* Root umuzu 7 olarak alırız.
* İlk olarak gelen 5 değeri, 7 den küçük olduğu için sola geçer.
* 1 değeri 7'den küçük olduğu için sola gider, 5'ten de küçük olduğu için 5'in sol altına yazılır.
* 8 değeri 7'den büyük olduğu için root un sağ altına geçer.
* 3 değeri 7'den küçük, 5'ten küçük ancak 1 den büyük olduğu için 1 in sağ altına yazılır.
* 6 değeri 7'den küçük, 5'ten büyük olduğu için 5'in sağ altına yazılır.
* 0 değeri 7'den 5'ten ve 1'den küçüktür, bu yüzden 1 in sol altına yazılır.
* 9 değeri 7'den ve 8'den büyüktür, bu yüzden 8'in sağ altına yazılır.
* 4 değeri 7'den ve 5'ten küçüktür, 1'den ve 3'ten büyüktür, bu yüzden 3 ün sağ altına yazılır.
* 2 değeri 7'den ve 5'ten küçüktür, 1'den büyük ama 3'ten küçüktür, bu yüzden 3'ün sol altına yazılır.