


# SI-and-Binary-Prefixes
Some brief information about SI and Binary Prefixes, which I cover in detail in 
my paper entitled [___SI and Binary Prefixes: Clearing the Confusion___](https://dl.acm.org/doi/10.1145/3572027)
published in the [Communications of the ACM](https://cacm.acm.org/magazines/2023/8/274934-si-and-binary-prefixes-clearing-the-confusion/abstract) journal.

Please refer to and cite the [___article___](https://dl.acm.org/doi/10.1145/3572027) for any information 
provided here. A citation example (APA style) can be found below:

Temiz, H. (2023). SI and Binary Prefixes: Clearing the Confusion. Communications of the ACM, 66(8), 29-31.

## Introduction


The International System of Units (SI) prefixes are defined to indicate multiples of a unit measurement by powers of 10. On the other hand, 
Binary Prefixes denote multiples of a unit (very most commonly used in computer science and information technologies) by power of 2.

Unfortunatelly, SI prefixes are very often **misused** to indicate to multiples of 2. Such that, a kilo (k) originally means a 1000 ($10^3$) of any unit,
but 1024 (2^10) in computer science, although the binary prefixes have already been defined to represent multiples of two.

International Electrotechnical Commission (IEC) has


<table>

<tr style="text-align: center;" >
<td colspan=3><p style="text-align: center;">SI Prefixes</p></td> <td style="width: 40px;" > &nbsp; </td>  <td colspan=3><p style="text-align: center;">Binary Prefixes</p></td>
</tr>
<tr>
<td>Symbol</td> <td>Name</td> <td>Value</td> <td></td> <td>Symbol</td> <td>Name</td><td>Value</td>
</tr>

<tr>
<td>Q</td> <td>quetta</td> <td>$10^{30}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>R</td> <td>ronna</td> <td>$10^{27}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>Y</td> <td>yotta</td> <td>$10^{24}$ &nbsp; $( = ({10^{3})}^{8} )$</td> <td></td> <td>Yi</td> <td>yobi</td><td>$2^{80}$  &nbsp; $( = ({2^{10})}^{8} )$</td>
</tr>

<tr>
<td>Z</td> <td>zetta</td> <td>$10^{21}$ &nbsp; $( = ({10^{3})}^{7} )$</td> <td></td> <td>Zi</td> <td>zebi</td><td>$2^{70}$  &nbsp; $( = ({2^{10})}^{7} )$</td>
</tr>

<tr>
<td>E</td> <td>exa</td> <td>$10^{18}$ &nbsp; $( = ({10^{3})}^{6} )$</td> <td></td> <td>Ei</td> <td>exbi</td><td>$2^{60}$  &nbsp; $( = ({2^{10})}^{6} )$</td>
</tr>

<tr>
<td>P</td> <td>peta</td> <td>$10^{15}$ &nbsp; $( = ({10^{3})}^{5} )$</td> <td></td> <td>Pi</td> <td>pebi</td><td>$2^{50}$  &nbsp; $( = ({2^{10})}^{5} )$</td>
</tr>

<tr>
<td>T</td> <td>tera</td> <td>$10^{12}$ &nbsp; $( = ({10^{3})}^{4} )$</td> <td></td> <td>Ti</td> <td>tebi</td><td>$2^{40}$  &nbsp; $( = ({2^{10})}^{4} )$</td>
</tr>

<tr>
<td>G</td> <td>giga</td> <td>$10^{9}$ &nbsp; $( = ({10^{3})}^{3} )$</td> <td></td> <td>Gi</td> <td>gibi</td><td>$2^{30}$  &nbsp; $( = ({2^{10})}^{3} )$</td>
</tr>

<tr>
<td>M</td> <td>mega</td> <td>$10^{6}$ &nbsp; $( = ({10^{3})}^{2} )$</td> <td></td> <td>Mi</td> <td>mebi</td><td>$2^{20}$  &nbsp; $( = ({2^{10})}^{2} )$</td>
</tr>

<tr>
<td>k</td> <td>kilo</td> <td>$10^{3}$ &nbsp; $( = ({10^{3})}^{1} )$</td> <td></td> <td>Ki</td> <td>kibi</td><td>$2^{10}$  &nbsp; $( = ({2^{10})}^{1} )$</td>
</tr>

<tr>
<td>h</td> <td>hecto</td> <td>$10^{2}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>da</td> <td>deca</td> <td>$10^{1}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>d</td> <td>deci</td> <td>$10^{-1}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>c</td> <td>centi</td> <td>$10^{-2}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>m</td> <td>milli</td> <td>$10^{-3}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>
<tr>
<td>µ</td> <td>micro</td> <td>$10^{-6}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>n</td> <td>nano</td> <td>$10^{-9}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>p</td> <td>pico</td> <td>$10^{-12}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>f</td> <td>femto</td> <td>$10^{-15}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>a</td> <td>atto</td> <td>$10^{-18}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>z</td> <td>zepto</td> <td>$10^{-21}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>y</td> <td>yocto</td> <td>$10^{-24}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>r</td> <td>ronto</td> <td>$10^{-27}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>

<tr>
<td>q</td> <td>quecto</td> <td>$10^{-30}$</td> <td></td> <td> </td> <td> </td><td> </td>
</tr>


</table>




<!--

<html>

<style>
.divTable
{
display: table;
width:auto;
background-color:#eee;
border:1px solid #666666;
border-spacing:1px;
}
.divRow
{
width:auto;
display:table-row;
}
.divCell
{
width:150px;
float:left;
display:table-column;
background-color: rgb(212, 209, 209);
}
</style>

<body>

<div class="divTable">
<div class="headerRow">
    <div class="divCell">Symbol</div> <div class="divCell">Name</div><div class="divCell">Value</div>
</div>
<div class="divRow">
    <div class="divCell">Y</div> <div class="divCell">yotto</div><div class="divCell">$$10^{24}</div>

</div>

</div>

</body>
</html>

-->

