# OpenStack 客户端命令行<a name="ZH-CN_TOPIC_0070864176"></a>

OpentStack组件与云服务的对应关系：

<a name="table56174843"></a>
<table><thead align="left"><tr id="row35752731"><th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.1"><p id="p10290070"><a name="p10290070"></a><a name="p10290070"></a>OpenStack组件</p>
</th>
<th class="cellrowborder" valign="top" width="50%" id="mcps1.1.3.1.2"><p id="p28189346"><a name="p28189346"></a><a name="p28189346"></a>云服务</p>
</th>
</tr>
</thead>
<tbody><tr id="row65381771"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p61432121"><a name="p61432121"></a><a name="p61432121"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p9945879"><a name="p9945879"></a><a name="p9945879"></a>IAM</p>
</td>
</tr>
<tr id="row2788537"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p24544935"><a name="p24544935"></a><a name="p24544935"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p41982722"><a name="p41982722"></a><a name="p41982722"></a>ECS</p>
</td>
</tr>
<tr id="row3762492"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p36326405"><a name="p36326405"></a><a name="p36326405"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p56757654"><a name="p56757654"></a><a name="p56757654"></a>VPC</p>
</td>
</tr>
<tr id="row37269850"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p66067912"><a name="p66067912"></a><a name="p66067912"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p49900666"><a name="p49900666"></a><a name="p49900666"></a>EVS</p>
</td>
</tr>
<tr id="row59043505"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p17794566"><a name="p17794566"></a><a name="p17794566"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p32073719"><a name="p32073719"></a><a name="p32073719"></a>IMS</p>
</td>
</tr>
<tr id="row09791247154316"><td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.1 "><p id="p1598034714430"><a name="p1598034714430"></a><a name="p1598034714430"></a>Designate</p>
</td>
<td class="cellrowborder" valign="top" width="50%" headers="mcps1.1.3.1.2 "><p id="p2098015478437"><a name="p2098015478437"></a><a name="p2098015478437"></a>DNS</p>
</td>
</tr>
</tbody>
</table>

## OpenStack Individual CLI<a name="section3373519420253"></a>

<a name="table2907789620253"></a>
<table><thead align="left"><tr id="row2127407020253"><th class="cellrowborder" valign="top" width="8.43%" id="mcps1.1.6.1.1"><p id="p152571917127"><a name="p152571917127"></a><a name="p152571917127"></a>序号</p>
</th>
<th class="cellrowborder" valign="top" width="15.409999999999998%" id="mcps1.1.6.1.2"><p id="p5842138520253"><a name="p5842138520253"></a><a name="p5842138520253"></a>组件</p>
</th>
<th class="cellrowborder" valign="top" width="31.36%" id="mcps1.1.6.1.3"><p id="p168621420253"><a name="p168621420253"></a><a name="p168621420253"></a>功能</p>
</th>
<th class="cellrowborder" valign="top" width="24.9%" id="mcps1.1.6.1.4"><p id="p2434822920253"><a name="p2434822920253"></a><a name="p2434822920253"></a>命令行</p>
</th>
<th class="cellrowborder" valign="top" width="19.900000000000002%" id="mcps1.1.6.1.5"><p id="p210879794332"><a name="p210879794332"></a><a name="p210879794332"></a>备注</p>
</th>
</tr>
</thead>
<tbody><tr id="row1095348020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12571317823"><a name="p12571317823"></a><a name="p12571317823"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1490888794724"><a name="p1490888794724"></a><a name="p1490888794724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6676919794724"><a name="p6676919794724"></a><a name="p6676919794724"></a>Create Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3959584794724"><a name="p3959584794724"></a><a name="p3959584794724"></a>nova boot</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5314702194724"><a name="p5314702194724"></a><a name="p5314702194724"></a>-</p>
</td>
</tr>
<tr id="row6052308120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p925712178216"><a name="p925712178216"></a><a name="p925712178216"></a>2</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2236446594724"><a name="p2236446594724"></a><a name="p2236446594724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6669127094724"><a name="p6669127094724"></a><a name="p6669127094724"></a>List Servers</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3328381294724"><a name="p3328381294724"></a><a name="p3328381294724"></a>nova list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1163422694724"><a name="p1163422694724"></a><a name="p1163422694724"></a>-</p>
</td>
</tr>
<tr id="row660112720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p325718171227"><a name="p325718171227"></a><a name="p325718171227"></a>3</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2563394894724"><a name="p2563394894724"></a><a name="p2563394894724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6308389894724"><a name="p6308389894724"></a><a name="p6308389894724"></a>Show Server Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p952211794724"><a name="p952211794724"></a><a name="p952211794724"></a>nova show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3309398894724"><a name="p3309398894724"></a><a name="p3309398894724"></a>-</p>
</td>
</tr>
<tr id="row653269020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p4257171715212"><a name="p4257171715212"></a><a name="p4257171715212"></a>4</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3343532894724"><a name="p3343532894724"></a><a name="p3343532894724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2390700994724"><a name="p2390700994724"></a><a name="p2390700994724"></a>Update Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5741957194724"><a name="p5741957194724"></a><a name="p5741957194724"></a>nova rename</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2047366194724"><a name="p2047366194724"></a><a name="p2047366194724"></a>-</p>
</td>
</tr>
<tr id="row1898277720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1525717174217"><a name="p1525717174217"></a><a name="p1525717174217"></a>5</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2713159794724"><a name="p2713159794724"></a><a name="p2713159794724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5017577294724"><a name="p5017577294724"></a><a name="p5017577294724"></a>Delete Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3770572794724"><a name="p3770572794724"></a><a name="p3770572794724"></a>nova delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3426505594724"><a name="p3426505594724"></a><a name="p3426505594724"></a>-</p>
</td>
</tr>
<tr id="row1776391720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p32571617524"><a name="p32571617524"></a><a name="p32571617524"></a>6</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1472787094724"><a name="p1472787094724"></a><a name="p1472787094724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5210683694724"><a name="p5210683694724"></a><a name="p5210683694724"></a>Resize Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5990419494724"><a name="p5990419494724"></a><a name="p5990419494724"></a>nova resize</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2040158594724"><a name="p2040158594724"></a><a name="p2040158594724"></a>-</p>
</td>
</tr>
<tr id="row5938738920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p152571917920"><a name="p152571917920"></a><a name="p152571917920"></a>7</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4169717194724"><a name="p4169717194724"></a><a name="p4169717194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2202770694724"><a name="p2202770694724"></a><a name="p2202770694724"></a>Confirm Resized Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3941379094724"><a name="p3941379094724"></a><a name="p3941379094724"></a>nova resize-confirm</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3840042294724"><a name="p3840042294724"></a><a name="p3840042294724"></a>-</p>
</td>
</tr>
<tr id="row5334316220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p02572017124"><a name="p02572017124"></a><a name="p02572017124"></a>8</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p951182994724"><a name="p951182994724"></a><a name="p951182994724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3226071294724"><a name="p3226071294724"></a><a name="p3226071294724"></a>Revert Resized Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6298085994724"><a name="p6298085994724"></a><a name="p6298085994724"></a>nova resize-revert</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p117592694724"><a name="p117592694724"></a><a name="p117592694724"></a>-</p>
</td>
</tr>
<tr id="row2363768320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p17257217124"><a name="p17257217124"></a><a name="p17257217124"></a>9</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5194408694724"><a name="p5194408694724"></a><a name="p5194408694724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4672140594724"><a name="p4672140594724"></a><a name="p4672140594724"></a>List Flavors</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2633748194724"><a name="p2633748194724"></a><a name="p2633748194724"></a>nova flavor-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5296125094724"><a name="p5296125094724"></a><a name="p5296125094724"></a>-</p>
</td>
</tr>
<tr id="row3950594520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p325711171022"><a name="p325711171022"></a><a name="p325711171022"></a>10</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2115486194724"><a name="p2115486194724"></a><a name="p2115486194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3582218094724"><a name="p3582218094724"></a><a name="p3582218094724"></a>Show Flavor Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1591545994724"><a name="p1591545994724"></a><a name="p1591545994724"></a>nova flavor-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1408382794724"><a name="p1408382794724"></a><a name="p1408382794724"></a>-</p>
</td>
</tr>
<tr id="row6695605920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p5257151717212"><a name="p5257151717212"></a><a name="p5257151717212"></a>11</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6656306994724"><a name="p6656306994724"></a><a name="p6656306994724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2289946994724"><a name="p2289946994724"></a><a name="p2289946994724"></a>Update or Delete Metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4291767394724"><a name="p4291767394724"></a><a name="p4291767394724"></a>nova meta</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5377951494724"><a name="p5377951494724"></a><a name="p5377951494724"></a>-</p>
</td>
</tr>
<tr id="row5991344920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p182571171121"><a name="p182571171121"></a><a name="p182571171121"></a>12</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1368983794724"><a name="p1368983794724"></a><a name="p1368983794724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3513502594724"><a name="p3513502594724"></a><a name="p3513502594724"></a>Stop Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2736474094724"><a name="p2736474094724"></a><a name="p2736474094724"></a>nova stop</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p195150594724"><a name="p195150594724"></a><a name="p195150594724"></a>-</p>
</td>
</tr>
<tr id="row575198920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p202571317821"><a name="p202571317821"></a><a name="p202571317821"></a>13</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1336126494724"><a name="p1336126494724"></a><a name="p1336126494724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p852059394724"><a name="p852059394724"></a><a name="p852059394724"></a>Start Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1907939894724"><a name="p1907939894724"></a><a name="p1907939894724"></a>nova start</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p192738394724"><a name="p192738394724"></a><a name="p192738394724"></a>-</p>
</td>
</tr>
<tr id="row4265258820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p625781719211"><a name="p625781719211"></a><a name="p625781719211"></a>14</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6288556694724"><a name="p6288556694724"></a><a name="p6288556694724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6056607094724"><a name="p6056607094724"></a><a name="p6056607094724"></a>Lock Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p690461494724"><a name="p690461494724"></a><a name="p690461494724"></a>nova lock</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2240287194724"><a name="p2240287194724"></a><a name="p2240287194724"></a>-</p>
</td>
</tr>
<tr id="row2803225620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p22573176217"><a name="p22573176217"></a><a name="p22573176217"></a>15</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2423938494724"><a name="p2423938494724"></a><a name="p2423938494724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1723307394724"><a name="p1723307394724"></a><a name="p1723307394724"></a>Unlock Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5370167194724"><a name="p5370167194724"></a><a name="p5370167194724"></a>nova unlock</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5486806594724"><a name="p5486806594724"></a><a name="p5486806594724"></a>-</p>
</td>
</tr>
<tr id="row1766140920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p925810171623"><a name="p925810171623"></a><a name="p925810171623"></a>16</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p193664794724"><a name="p193664794724"></a><a name="p193664794724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2265071594724"><a name="p2265071594724"></a><a name="p2265071594724"></a>Get Server Action By Request ID</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2276865694724"><a name="p2276865694724"></a><a name="p2276865694724"></a>nova instance-action</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3232187094724"><a name="p3232187094724"></a><a name="p3232187094724"></a>-</p>
</td>
</tr>
<tr id="row2807948620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p525812178212"><a name="p525812178212"></a><a name="p525812178212"></a>17</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p743209294724"><a name="p743209294724"></a><a name="p743209294724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6512859894724"><a name="p6512859894724"></a><a name="p6512859894724"></a>List Servers Action</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4092507694724"><a name="p4092507694724"></a><a name="p4092507694724"></a>nova instance-action-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2659686394724"><a name="p2659686394724"></a><a name="p2659686394724"></a>-</p>
</td>
</tr>
<tr id="row505575220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p02584176211"><a name="p02584176211"></a><a name="p02584176211"></a>18</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6176043394724"><a name="p6176043394724"></a><a name="p6176043394724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3653914694724"><a name="p3653914694724"></a><a name="p3653914694724"></a>Attach Volume</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p688081194724"><a name="p688081194724"></a><a name="p688081194724"></a>nova volume-attach</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2047481394724"><a name="p2047481394724"></a><a name="p2047481394724"></a>-</p>
</td>
</tr>
<tr id="row4842692620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p15258161719212"><a name="p15258161719212"></a><a name="p15258161719212"></a>19</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2797110994724"><a name="p2797110994724"></a><a name="p2797110994724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5106736794724"><a name="p5106736794724"></a><a name="p5106736794724"></a>Detach Volume</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4281608694724"><a name="p4281608694724"></a><a name="p4281608694724"></a>nova volume-detach</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4555093794724"><a name="p4555093794724"></a><a name="p4555093794724"></a>-</p>
</td>
</tr>
<tr id="row411920120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p14258171720212"><a name="p14258171720212"></a><a name="p14258171720212"></a>20</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5485469194724"><a name="p5485469194724"></a><a name="p5485469194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1404496894724"><a name="p1404496894724"></a><a name="p1404496894724"></a>List Keypairs</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6390063894724"><a name="p6390063894724"></a><a name="p6390063894724"></a>nova keypair-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p856919694724"><a name="p856919694724"></a><a name="p856919694724"></a>-</p>
</td>
</tr>
<tr id="row1719016020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p5258617324"><a name="p5258617324"></a><a name="p5258617324"></a>21</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p582025194724"><a name="p582025194724"></a><a name="p582025194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p167828594724"><a name="p167828594724"></a><a name="p167828594724"></a>Add Keypair</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p172341294724"><a name="p172341294724"></a><a name="p172341294724"></a>nova keypair-add</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p537871294724"><a name="p537871294724"></a><a name="p537871294724"></a>-</p>
</td>
</tr>
<tr id="row1584746820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p42581717327"><a name="p42581717327"></a><a name="p42581717327"></a>22</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2876730194724"><a name="p2876730194724"></a><a name="p2876730194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4845007994724"><a name="p4845007994724"></a><a name="p4845007994724"></a>Show Keypair Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3214235494724"><a name="p3214235494724"></a><a name="p3214235494724"></a>nova keypair-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5339386194724"><a name="p5339386194724"></a><a name="p5339386194724"></a>-</p>
</td>
</tr>
<tr id="row5582416420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12584171223"><a name="p12584171223"></a><a name="p12584171223"></a>23</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p98365294724"><a name="p98365294724"></a><a name="p98365294724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1256702494724"><a name="p1256702494724"></a><a name="p1256702494724"></a>Delete Keypair</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1129599194724"><a name="p1129599194724"></a><a name="p1129599194724"></a>nova keypair-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4256009994724"><a name="p4256009994724"></a><a name="p4256009994724"></a>-</p>
</td>
</tr>
<tr id="row3193834520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1258141717210"><a name="p1258141717210"></a><a name="p1258141717210"></a>24</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2201766594724"><a name="p2201766594724"></a><a name="p2201766594724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3860040794724"><a name="p3860040794724"></a><a name="p3860040794724"></a>Show Quota Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3962526294724"><a name="p3962526294724"></a><a name="p3962526294724"></a>nova quota-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5552964594724"><a name="p5552964594724"></a><a name="p5552964594724"></a>-</p>
</td>
</tr>
<tr id="row1512842620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p92582171522"><a name="p92582171522"></a><a name="p92582171522"></a>25</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1446679594724"><a name="p1446679594724"></a><a name="p1446679594724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3095973594724"><a name="p3095973594724"></a><a name="p3095973594724"></a>Show Default Quota Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2471056794724"><a name="p2471056794724"></a><a name="p2471056794724"></a>nova quota-defaults</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5539888394724"><a name="p5539888394724"></a><a name="p5539888394724"></a>-</p>
</td>
</tr>
<tr id="row5733608720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p92581717526"><a name="p92581717526"></a><a name="p92581717526"></a>26</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5335903694724"><a name="p5335903694724"></a><a name="p5335903694724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2711467994724"><a name="p2711467994724"></a><a name="p2711467994724"></a>Attach Interface</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4880540394724"><a name="p4880540394724"></a><a name="p4880540394724"></a>nova interface-attach</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6092353494724"><a name="p6092353494724"></a><a name="p6092353494724"></a>-</p>
</td>
</tr>
<tr id="row5143945820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p8258131711218"><a name="p8258131711218"></a><a name="p8258131711218"></a>27</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5429787894724"><a name="p5429787894724"></a><a name="p5429787894724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3605197894724"><a name="p3605197894724"></a><a name="p3605197894724"></a>List Port Interfaces</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3452909994724"><a name="p3452909994724"></a><a name="p3452909994724"></a>nova interface-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4539360094724"><a name="p4539360094724"></a><a name="p4539360094724"></a>-</p>
</td>
</tr>
<tr id="row3211250420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p325811175210"><a name="p325811175210"></a><a name="p325811175210"></a>28</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p726460894724"><a name="p726460894724"></a><a name="p726460894724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5156240894724"><a name="p5156240894724"></a><a name="p5156240894724"></a>Detach Interface</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1580550494724"><a name="p1580550494724"></a><a name="p1580550494724"></a>nova interface-detach</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p517742494724"><a name="p517742494724"></a><a name="p517742494724"></a>-</p>
</td>
</tr>
<tr id="row2841818720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p14258191713210"><a name="p14258191713210"></a><a name="p14258191713210"></a>29</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1624615794724"><a name="p1624615794724"></a><a name="p1624615794724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4087035494724"><a name="p4087035494724"></a><a name="p4087035494724"></a>Show Server Password Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2216436394724"><a name="p2216436394724"></a><a name="p2216436394724"></a>nova get-password</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5048297794724"><a name="p5048297794724"></a><a name="p5048297794724"></a>-</p>
</td>
</tr>
<tr id="row5533793120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p2258151714218"><a name="p2258151714218"></a><a name="p2258151714218"></a>30</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2643285394724"><a name="p2643285394724"></a><a name="p2643285394724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6068635394724"><a name="p6068635394724"></a><a name="p6068635394724"></a>Clear Admin Password</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1664755794724"><a name="p1664755794724"></a><a name="p1664755794724"></a>nova clear-password</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p627490694724"><a name="p627490694724"></a><a name="p627490694724"></a>-</p>
</td>
</tr>
<tr id="row2613360720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p4258101710215"><a name="p4258101710215"></a><a name="p4258101710215"></a>31</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1100428194724"><a name="p1100428194724"></a><a name="p1100428194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1893157494724"><a name="p1893157494724"></a><a name="p1893157494724"></a>Create Image</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5706254494724"><a name="p5706254494724"></a><a name="p5706254494724"></a>nova image-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5866334294724"><a name="p5866334294724"></a><a name="p5866334294724"></a>-</p>
</td>
</tr>
<tr id="row3852686420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p152586171429"><a name="p152586171429"></a><a name="p152586171429"></a>32</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1723033894724"><a name="p1723033894724"></a><a name="p1723033894724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5348015594724"><a name="p5348015594724"></a><a name="p5348015594724"></a>List Images</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3692526894724"><a name="p3692526894724"></a><a name="p3692526894724"></a>nova image-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3815669394724"><a name="p3815669394724"></a><a name="p3815669394724"></a>-</p>
</td>
</tr>
<tr id="row1128562120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1258171719214"><a name="p1258171719214"></a><a name="p1258171719214"></a>33</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3315980994724"><a name="p3315980994724"></a><a name="p3315980994724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p159004794724"><a name="p159004794724"></a><a name="p159004794724"></a>Show Image Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6168499394724"><a name="p6168499394724"></a><a name="p6168499394724"></a>nova image-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p729012211260"><a name="p729012211260"></a><a name="p729012211260"></a>-</p>
</td>
</tr>
<tr id="row6372666320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p225813171223"><a name="p225813171223"></a><a name="p225813171223"></a>34</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3649544094724"><a name="p3649544094724"></a><a name="p3649544094724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p334065394724"><a name="p334065394724"></a><a name="p334065394724"></a>Delete Image</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p215745894724"><a name="p215745894724"></a><a name="p215745894724"></a>nova image-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p185115217261"><a name="p185115217261"></a><a name="p185115217261"></a>-</p>
</td>
</tr>
<tr id="row1074437320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p125819179216"><a name="p125819179216"></a><a name="p125819179216"></a>35</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2315335894724"><a name="p2315335894724"></a><a name="p2315335894724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6348274194724"><a name="p6348274194724"></a><a name="p6348274194724"></a>Reboot Server Hard</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4182835994724"><a name="p4182835994724"></a><a name="p4182835994724"></a>nova reboot --hard</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p197263282613"><a name="p197263282613"></a><a name="p197263282613"></a>-</p>
</td>
</tr>
<tr id="row3696318420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12581217325"><a name="p12581217325"></a><a name="p12581217325"></a>36</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4818064694724"><a name="p4818064694724"></a><a name="p4818064694724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1031825594724"><a name="p1031825594724"></a><a name="p1031825594724"></a>Reboot Server Soft</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3047236194724"><a name="p3047236194724"></a><a name="p3047236194724"></a>nova reboot</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1794816213262"><a name="p1794816213262"></a><a name="p1794816213262"></a>-</p>
</td>
</tr>
<tr id="row5020855120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p142585177219"><a name="p142585177219"></a><a name="p142585177219"></a>37</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3963213694724"><a name="p3963213694724"></a><a name="p3963213694724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5608643094724"><a name="p5608643094724"></a><a name="p5608643094724"></a>List Attached Volumes</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4670701894724"><a name="p4670701894724"></a><a name="p4670701894724"></a>nova volume-attachments</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4159432261"><a name="p4159432261"></a><a name="p4159432261"></a>-</p>
</td>
</tr>
<tr id="row4632948220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p172581176219"><a name="p172581176219"></a><a name="p172581176219"></a>38</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2972772594724"><a name="p2972772594724"></a><a name="p2972772594724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5913549994724"><a name="p5913549994724"></a><a name="p5913549994724"></a>List Networks</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2524608194724"><a name="p2524608194724"></a><a name="p2524608194724"></a>nova network-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6362031267"><a name="p6362031267"></a><a name="p6362031267"></a>-</p>
</td>
</tr>
<tr id="row5930925920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1225821714216"><a name="p1225821714216"></a><a name="p1225821714216"></a>39</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6666965494724"><a name="p6666965494724"></a><a name="p6666965494724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3153286994724"><a name="p3153286994724"></a><a name="p3153286994724"></a>Create Security Group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p402558594724"><a name="p402558594724"></a><a name="p402558594724"></a>nova secgroup-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p185964318266"><a name="p185964318266"></a><a name="p185964318266"></a>-</p>
</td>
</tr>
<tr id="row1543144720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1725813171227"><a name="p1725813171227"></a><a name="p1725813171227"></a>40</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p717249294724"><a name="p717249294724"></a><a name="p717249294724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4410096694724"><a name="p4410096694724"></a><a name="p4410096694724"></a>Delete Security Group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1540851394724"><a name="p1540851394724"></a><a name="p1540851394724"></a>nova secgroup-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p83036432612"><a name="p83036432612"></a><a name="p83036432612"></a>-</p>
</td>
</tr>
<tr id="row1159491220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12583171321"><a name="p12583171321"></a><a name="p12583171321"></a>41</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6245283294724"><a name="p6245283294724"></a><a name="p6245283294724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2551464094724"><a name="p2551464094724"></a><a name="p2551464094724"></a>List Security Group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5341994094724"><a name="p5341994094724"></a><a name="p5341994094724"></a>nova secgroup-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p84200918265"><a name="p84200918265"></a><a name="p84200918265"></a>-</p>
</td>
</tr>
<tr id="row6147650220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p92581717926"><a name="p92581717926"></a><a name="p92581717926"></a>42</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p901770794724"><a name="p901770794724"></a><a name="p901770794724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5934570694724"><a name="p5934570694724"></a><a name="p5934570694724"></a>Create Security Group Rule</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4227291494724"><a name="p4227291494724"></a><a name="p4227291494724"></a>nova secgroup-add-rule</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p11660395267"><a name="p11660395267"></a><a name="p11660395267"></a>-</p>
</td>
</tr>
<tr id="row3096170420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p122586177218"><a name="p122586177218"></a><a name="p122586177218"></a>43</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5911995194724"><a name="p5911995194724"></a><a name="p5911995194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2398672794724"><a name="p2398672794724"></a><a name="p2398672794724"></a>Delete Security Group Rule</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6387674894724"><a name="p6387674894724"></a><a name="p6387674894724"></a>nova secgroup-delete-rule</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p18886189192615"><a name="p18886189192615"></a><a name="p18886189192615"></a>-</p>
</td>
</tr>
<tr id="row1450151120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p125810171421"><a name="p125810171421"></a><a name="p125810171421"></a>44</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p441010094724"><a name="p441010094724"></a><a name="p441010094724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2167379194724"><a name="p2167379194724"></a><a name="p2167379194724"></a>Create Server Group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1074665194724"><a name="p1074665194724"></a><a name="p1074665194724"></a>nova server-group-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1511541012267"><a name="p1511541012267"></a><a name="p1511541012267"></a>-</p>
</td>
</tr>
<tr id="row6187645020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p6258917526"><a name="p6258917526"></a><a name="p6258917526"></a>45</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6471265094724"><a name="p6471265094724"></a><a name="p6471265094724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p723333194724"><a name="p723333194724"></a><a name="p723333194724"></a>List Server Groups</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4902894494724"><a name="p4902894494724"></a><a name="p4902894494724"></a>nova server-group-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p635001002612"><a name="p635001002612"></a><a name="p635001002612"></a>-</p>
</td>
</tr>
<tr id="row4389693820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12581517123"><a name="p12581517123"></a><a name="p12581517123"></a>46</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3376385294724"><a name="p3376385294724"></a><a name="p3376385294724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5051751694724"><a name="p5051751694724"></a><a name="p5051751694724"></a>Get Server Group Detail</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6538701394724"><a name="p6538701394724"></a><a name="p6538701394724"></a>nova server-group-get</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1157351052615"><a name="p1157351052615"></a><a name="p1157351052615"></a>-</p>
</td>
</tr>
<tr id="row4291591820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p82580173216"><a name="p82580173216"></a><a name="p82580173216"></a>47</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6346469894724"><a name="p6346469894724"></a><a name="p6346469894724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4036693994724"><a name="p4036693994724"></a><a name="p4036693994724"></a>Delete Server Group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4849666594724"><a name="p4849666594724"></a><a name="p4849666594724"></a>nova server-group-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6791161013263"><a name="p6791161013263"></a><a name="p6791161013263"></a>-</p>
</td>
</tr>
<tr id="row4341702320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p325818176215"><a name="p325818176215"></a><a name="p325818176215"></a>48</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1016399794724"><a name="p1016399794724"></a><a name="p1016399794724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1797746694724"><a name="p1797746694724"></a><a name="p1797746694724"></a>Rebuild Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4688863194724"><a name="p4688863194724"></a><a name="p4688863194724"></a>nova rebuild</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p410111162619"><a name="p410111162619"></a><a name="p410111162619"></a>-</p>
</td>
</tr>
<tr id="row4675172420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p92589171122"><a name="p92589171122"></a><a name="p92589171122"></a>49</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1638567194724"><a name="p1638567194724"></a><a name="p1638567194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5217095294724"><a name="p5217095294724"></a><a name="p5217095294724"></a>Show Absolute Limits</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6509761594724"><a name="p6509761594724"></a><a name="p6509761594724"></a>nova limits</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p38706167264"><a name="p38706167264"></a><a name="p38706167264"></a>-</p>
</td>
</tr>
<tr id="row5637734920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p172582175210"><a name="p172582175210"></a><a name="p172582175210"></a>50</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2044903994724"><a name="p2044903994724"></a><a name="p2044903994724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4575947294724"><a name="p4575947294724"></a><a name="p4575947294724"></a>Associate Floating IP with Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1552975394724"><a name="p1552975394724"></a><a name="p1552975394724"></a>nova floating-ip-associate</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p159151772616"><a name="p159151772616"></a><a name="p159151772616"></a>-</p>
</td>
</tr>
<tr id="row5103647620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p52587171329"><a name="p52587171329"></a><a name="p52587171329"></a>51</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4092175294724"><a name="p4092175294724"></a><a name="p4092175294724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2632758694724"><a name="p2632758694724"></a><a name="p2632758694724"></a>Dissociate Floating IP From Server</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5215970494724"><a name="p5215970494724"></a><a name="p5215970494724"></a>nova floating-ip-disassociate</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1632215175260"><a name="p1632215175260"></a><a name="p1632215175260"></a>-</p>
</td>
</tr>
<tr id="row6331820620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p2258817727"><a name="p2258817727"></a><a name="p2258817727"></a>52</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1710368994724"><a name="p1710368994724"></a><a name="p1710368994724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4322159194724"><a name="p4322159194724"></a><a name="p4322159194724"></a>List Floating Ips</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1128795794724"><a name="p1128795794724"></a><a name="p1128795794724"></a>nova flaoting-ip-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1555514172269"><a name="p1555514172269"></a><a name="p1555514172269"></a>-</p>
</td>
</tr>
<tr id="row1127980620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p8258151711212"><a name="p8258151711212"></a><a name="p8258151711212"></a>53</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1734037394724"><a name="p1734037394724"></a><a name="p1734037394724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6239297694724"><a name="p6239297694724"></a><a name="p6239297694724"></a>List API Versions</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2066627194724"><a name="p2066627194724"></a><a name="p2066627194724"></a>nova version-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p676510174266"><a name="p676510174266"></a><a name="p676510174266"></a>-</p>
</td>
</tr>
<tr id="row454896920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p82582172027"><a name="p82582172027"></a><a name="p82582172027"></a>54</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1507371694724"><a name="p1507371694724"></a><a name="p1507371694724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1301147894724"><a name="p1301147894724"></a><a name="p1301147894724"></a>Update Security Group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4729678494724"><a name="p4729678494724"></a><a name="p4729678494724"></a>nova secgroup-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1798521782612"><a name="p1798521782612"></a><a name="p1798521782612"></a>-</p>
</td>
</tr>
<tr id="row3438769720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p325811716217"><a name="p325811716217"></a><a name="p325811716217"></a>55</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2535767194724"><a name="p2535767194724"></a><a name="p2535767194724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4070546694724"><a name="p4070546694724"></a><a name="p4070546694724"></a>List Server Security Groups</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p880845894724"><a name="p880845894724"></a><a name="p880845894724"></a>nova list-secgroup</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p17211161811266"><a name="p17211161811266"></a><a name="p17211161811266"></a>-</p>
</td>
</tr>
<tr id="row3757351020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p162584175212"><a name="p162584175212"></a><a name="p162584175212"></a>56</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3695531994724"><a name="p3695531994724"></a><a name="p3695531994724"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4059086994724"><a name="p4059086994724"></a><a name="p4059086994724"></a>List Floating Ip Pools</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6663499694724"><a name="p6663499694724"></a><a name="p6663499694724"></a>nova floating-ip-pool-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1542319183267"><a name="p1542319183267"></a><a name="p1542319183267"></a>-</p>
</td>
</tr>
<tr id="row4888533520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1125821710215"><a name="p1125821710215"></a><a name="p1125821710215"></a>57</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p301746194724"><a name="p301746194724"></a><a name="p301746194724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4308781794724"><a name="p4308781794724"></a><a name="p4308781794724"></a>Create Volume</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p45228994724"><a name="p45228994724"></a><a name="p45228994724"></a>cinder create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3663546294724"><a name="p3663546294724"></a><a name="p3663546294724"></a>-</p>
</td>
</tr>
<tr id="row4065836720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p132588175211"><a name="p132588175211"></a><a name="p132588175211"></a>58</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6503301994724"><a name="p6503301994724"></a><a name="p6503301994724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3318316694724"><a name="p3318316694724"></a><a name="p3318316694724"></a>List Volumes</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p348189794724"><a name="p348189794724"></a><a name="p348189794724"></a>cinder list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1359824594724"><a name="p1359824594724"></a><a name="p1359824594724"></a>-</p>
</td>
</tr>
<tr id="row6330271720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p325815171322"><a name="p325815171322"></a><a name="p325815171322"></a>59</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4811792894724"><a name="p4811792894724"></a><a name="p4811792894724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p523811694724"><a name="p523811694724"></a><a name="p523811694724"></a>Delete Volume</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2163428594724"><a name="p2163428594724"></a><a name="p2163428594724"></a>cinder delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p754666694724"><a name="p754666694724"></a><a name="p754666694724"></a>-</p>
</td>
</tr>
<tr id="row1611067520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p3258517129"><a name="p3258517129"></a><a name="p3258517129"></a>60</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6570205594724"><a name="p6570205594724"></a><a name="p6570205594724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2026623094724"><a name="p2026623094724"></a><a name="p2026623094724"></a>Show Volume Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3095195894724"><a name="p3095195894724"></a><a name="p3095195894724"></a>cinder show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2408068794724"><a name="p2408068794724"></a><a name="p2408068794724"></a>-</p>
</td>
</tr>
<tr id="row30760120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p22582171521"><a name="p22582171521"></a><a name="p22582171521"></a>61</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3940740094724"><a name="p3940740094724"></a><a name="p3940740094724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3788280494724"><a name="p3788280494724"></a><a name="p3788280494724"></a>Show Volume Metadata Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4860830994724"><a name="p4860830994724"></a><a name="p4860830994724"></a>cinder metadata-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4495899594724"><a name="p4495899594724"></a><a name="p4495899594724"></a>-</p>
</td>
</tr>
<tr id="row5466356120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p82587176213"><a name="p82587176213"></a><a name="p82587176213"></a>62</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2598218094724"><a name="p2598218094724"></a><a name="p2598218094724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2418179994724"><a name="p2418179994724"></a><a name="p2418179994724"></a>Update Volume Metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1256874094724"><a name="p1256874094724"></a><a name="p1256874094724"></a>cinder metadata</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1143500994724"><a name="p1143500994724"></a><a name="p1143500994724"></a>You can update only the volume metadata, namely, you can set only the value of action in the CLI.</p>
</td>
</tr>
<tr id="row4550067820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1825814179213"><a name="p1825814179213"></a><a name="p1825814179213"></a>63</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1462262094724"><a name="p1462262094724"></a><a name="p1462262094724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4358153794724"><a name="p4358153794724"></a><a name="p4358153794724"></a>List Snapshots</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4044358694724"><a name="p4044358694724"></a><a name="p4044358694724"></a>cinder snapshot-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5470506594724"><a name="p5470506594724"></a><a name="p5470506594724"></a>-</p>
</td>
</tr>
<tr id="row1893350620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p10258161711212"><a name="p10258161711212"></a><a name="p10258161711212"></a>64</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1732719394724"><a name="p1732719394724"></a><a name="p1732719394724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6132536994724"><a name="p6132536994724"></a><a name="p6132536994724"></a>Delete snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p129900294724"><a name="p129900294724"></a><a name="p129900294724"></a>cinder snapshot-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3811033994724"><a name="p3811033994724"></a><a name="p3811033994724"></a>-</p>
</td>
</tr>
<tr id="row1287703120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p02581517127"><a name="p02581517127"></a><a name="p02581517127"></a>65</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6647697294724"><a name="p6647697294724"></a><a name="p6647697294724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1592565094724"><a name="p1592565094724"></a><a name="p1592565094724"></a>Show snapshot Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1490924494724"><a name="p1490924494724"></a><a name="p1490924494724"></a>cinder snapshot-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6679809894724"><a name="p6679809894724"></a><a name="p6679809894724"></a>-</p>
</td>
</tr>
<tr id="row3773037220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p125811175210"><a name="p125811175210"></a><a name="p125811175210"></a>66</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4188772694724"><a name="p4188772694724"></a><a name="p4188772694724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3746267594724"><a name="p3746267594724"></a><a name="p3746267594724"></a>Create snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1457785794724"><a name="p1457785794724"></a><a name="p1457785794724"></a>cinder snapshot-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3995574394724"><a name="p3995574394724"></a><a name="p3995574394724"></a>-</p>
</td>
</tr>
<tr id="row3286852220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p225818174213"><a name="p225818174213"></a><a name="p225818174213"></a>67</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p248972994724"><a name="p248972994724"></a><a name="p248972994724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p34148794724"><a name="p34148794724"></a><a name="p34148794724"></a>Show Quota Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2766049094724"><a name="p2766049094724"></a><a name="p2766049094724"></a>cinder quota-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2590719394724"><a name="p2590719394724"></a><a name="p2590719394724"></a>-</p>
</td>
</tr>
<tr id="row2188386620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12582170215"><a name="p12582170215"></a><a name="p12582170215"></a>68</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2875316594724"><a name="p2875316594724"></a><a name="p2875316594724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4730499094724"><a name="p4730499094724"></a><a name="p4730499094724"></a>List Backups</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p649897694724"><a name="p649897694724"></a><a name="p649897694724"></a>cinder backup-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5665503494724"><a name="p5665503494724"></a><a name="p5665503494724"></a>-</p>
</td>
</tr>
<tr id="row5183109720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1025818174210"><a name="p1025818174210"></a><a name="p1025818174210"></a>69</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2956896294724"><a name="p2956896294724"></a><a name="p2956896294724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4627574594724"><a name="p4627574594724"></a><a name="p4627574594724"></a>Show Backup Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5734786094724"><a name="p5734786094724"></a><a name="p5734786094724"></a>cinder backup-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1466509294724"><a name="p1466509294724"></a><a name="p1466509294724"></a>-</p>
</td>
</tr>
<tr id="row2137048120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p02584171326"><a name="p02584171326"></a><a name="p02584171326"></a>70</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2054287594724"><a name="p2054287594724"></a><a name="p2054287594724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5336019394724"><a name="p5336019394724"></a><a name="p5336019394724"></a>Delete Backup</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2720838394724"><a name="p2720838394724"></a><a name="p2720838394724"></a>cinder backup-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5639545494724"><a name="p5639545494724"></a><a name="p5639545494724"></a>-</p>
</td>
</tr>
<tr id="row5466702620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1325851714215"><a name="p1325851714215"></a><a name="p1325851714215"></a>71</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4166184894724"><a name="p4166184894724"></a><a name="p4166184894724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1916654394724"><a name="p1916654394724"></a><a name="p1916654394724"></a>Extend Volume</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p898617994724"><a name="p898617994724"></a><a name="p898617994724"></a>cinder extend</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5679189994724"><a name="p5679189994724"></a><a name="p5679189994724"></a>-</p>
</td>
</tr>
<tr id="row5044241120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p132586171725"><a name="p132586171725"></a><a name="p132586171725"></a>72</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6223462694724"><a name="p6223462694724"></a><a name="p6223462694724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p783997394724"><a name="p783997394724"></a><a name="p783997394724"></a>Update Volume</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3105805694724"><a name="p3105805694724"></a><a name="p3105805694724"></a>cinder rename</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3267457994724"><a name="p3267457994724"></a><a name="p3267457994724"></a>-</p>
</td>
</tr>
<tr id="row5581916320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p20258317127"><a name="p20258317127"></a><a name="p20258317127"></a>73</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6323063594724"><a name="p6323063594724"></a><a name="p6323063594724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2140777894724"><a name="p2140777894724"></a><a name="p2140777894724"></a>Update snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5630847894724"><a name="p5630847894724"></a><a name="p5630847894724"></a>cinder snapshot-rename</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6469290394724"><a name="p6469290394724"></a><a name="p6469290394724"></a>-</p>
</td>
</tr>
<tr id="row5665221720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12258317620"><a name="p12258317620"></a><a name="p12258317620"></a>74</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5070417094724"><a name="p5070417094724"></a><a name="p5070417094724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1339710594724"><a name="p1339710594724"></a><a name="p1339710594724"></a>Create metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1142371294724"><a name="p1142371294724"></a><a name="p1142371294724"></a>cinder snapshot-metadata</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5290550494724"><a name="p5290550494724"></a><a name="p5290550494724"></a>action=set</p>
</td>
</tr>
<tr id="row3200768020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1825812173212"><a name="p1825812173212"></a><a name="p1825812173212"></a>75</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4762499494724"><a name="p4762499494724"></a><a name="p4762499494724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3241926694724"><a name="p3241926694724"></a><a name="p3241926694724"></a>Show snapshot metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p871486294724"><a name="p871486294724"></a><a name="p871486294724"></a>cinder snapshot-metadata-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3481524794724"><a name="p3481524794724"></a><a name="p3481524794724"></a>-</p>
</td>
</tr>
<tr id="row192051120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p10258517629"><a name="p10258517629"></a><a name="p10258517629"></a>76</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1316517894724"><a name="p1316517894724"></a><a name="p1316517894724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5974651094724"><a name="p5974651094724"></a><a name="p5974651094724"></a>Update snapshot metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p762910594724"><a name="p762910594724"></a><a name="p762910594724"></a>cinder snapshot-metadata-update-all</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1397780694724"><a name="p1397780694724"></a><a name="p1397780694724"></a>-</p>
</td>
</tr>
<tr id="row1455751020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p2258171710214"><a name="p2258171710214"></a><a name="p2258171710214"></a>77</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5638237394724"><a name="p5638237394724"></a><a name="p5638237394724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p356949494724"><a name="p356949494724"></a><a name="p356949494724"></a>Delete snapshot metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2069356394724"><a name="p2069356394724"></a><a name="p2069356394724"></a>cinder snapshot-metadata</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6556588494724"><a name="p6556588494724"></a><a name="p6556588494724"></a>action=unset</p>
</td>
</tr>
<tr id="row1267133520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p925818171429"><a name="p925818171429"></a><a name="p925818171429"></a>78</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1601890794724"><a name="p1601890794724"></a><a name="p1601890794724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2246307594724"><a name="p2246307594724"></a><a name="p2246307594724"></a>Update Volume Metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p756976394724"><a name="p756976394724"></a><a name="p756976394724"></a>cinder metadata-update-all</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p917107694724"><a name="p917107694724"></a><a name="p917107694724"></a>-</p>
</td>
</tr>
<tr id="row2773451120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p32589171218"><a name="p32589171218"></a><a name="p32589171218"></a>79</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4193724594724"><a name="p4193724594724"></a><a name="p4193724594724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4147367094724"><a name="p4147367094724"></a><a name="p4147367094724"></a>Set volume bootable</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p392410894724"><a name="p392410894724"></a><a name="p392410894724"></a>cinder set-bootable</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4941730294724"><a name="p4941730294724"></a><a name="p4941730294724"></a>-</p>
</td>
</tr>
<tr id="row4744203220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1525821711212"><a name="p1525821711212"></a><a name="p1525821711212"></a>80</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5486226094724"><a name="p5486226094724"></a><a name="p5486226094724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1465807294724"><a name="p1465807294724"></a><a name="p1465807294724"></a>Set volume readonly</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4645321394724"><a name="p4645321394724"></a><a name="p4645321394724"></a>cinder readonly-mode-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p461393194724"><a name="p461393194724"></a><a name="p461393194724"></a>-</p>
</td>
</tr>
<tr id="row5686284420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p12582171021"><a name="p12582171021"></a><a name="p12582171021"></a>81</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p811262594724"><a name="p811262594724"></a><a name="p811262594724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5314290794724"><a name="p5314290794724"></a><a name="p5314290794724"></a>List api extensions</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p960820194724"><a name="p960820194724"></a><a name="p960820194724"></a>cinder list-extensions</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4006682094724"><a name="p4006682094724"></a><a name="p4006682094724"></a>-</p>
</td>
</tr>
<tr id="row3459996320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p142595171223"><a name="p142595171223"></a><a name="p142595171223"></a>82</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1635607894724"><a name="p1635607894724"></a><a name="p1635607894724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4977391194724"><a name="p4977391194724"></a><a name="p4977391194724"></a>Querying EVS disk types</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p515495294724"><a name="p515495294724"></a><a name="p515495294724"></a>cinder type-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1489796294724"><a name="p1489796294724"></a><a name="p1489796294724"></a>-</p>
</td>
</tr>
<tr id="row6550517120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p142591717323"><a name="p142591717323"></a><a name="p142591717323"></a>83</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5608743494724"><a name="p5608743494724"></a><a name="p5608743494724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4678831694724"><a name="p4678831694724"></a><a name="p4678831694724"></a>Querying details about an EVS disk type</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3175727594724"><a name="p3175727594724"></a><a name="p3175727594724"></a>cinder type-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2220247894724"><a name="p2220247894724"></a><a name="p2220247894724"></a>-</p>
</td>
</tr>
<tr id="row4154942820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p425919171123"><a name="p425919171123"></a><a name="p425919171123"></a>84</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1237067294724"><a name="p1237067294724"></a><a name="p1237067294724"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6250035794724"><a name="p6250035794724"></a><a name="p6250035794724"></a>Restore backup</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2936417194724"><a name="p2936417194724"></a><a name="p2936417194724"></a>cinder backup-restore</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2968765794724"><a name="p2968765794724"></a><a name="p2968765794724"></a>-</p>
</td>
</tr>
<tr id="row45626920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p925911171423"><a name="p925911171423"></a><a name="p925911171423"></a>85</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3324846494724"><a name="p3324846494724"></a><a name="p3324846494724"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p877102694724"><a name="p877102694724"></a><a name="p877102694724"></a>Show Image Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3936452194724"><a name="p3936452194724"></a><a name="p3936452194724"></a>glance image-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3440966194724"><a name="p3440966194724"></a><a name="p3440966194724"></a>-</p>
</td>
</tr>
<tr id="row4406033520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p62596172212"><a name="p62596172212"></a><a name="p62596172212"></a>86</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5303696294724"><a name="p5303696294724"></a><a name="p5303696294724"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p102670094724"><a name="p102670094724"></a><a name="p102670094724"></a>List Images</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1605390394724"><a name="p1605390394724"></a><a name="p1605390394724"></a>glance image-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2529774694724"><a name="p2529774694724"></a><a name="p2529774694724"></a>-</p>
</td>
</tr>
<tr id="row3239191520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1225917179216"><a name="p1225917179216"></a><a name="p1225917179216"></a>87</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5422820194724"><a name="p5422820194724"></a><a name="p5422820194724"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3040819794724"><a name="p3040819794724"></a><a name="p3040819794724"></a>Delete Image</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4714486094724"><a name="p4714486094724"></a><a name="p4714486094724"></a>glance image-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6063733694724"><a name="p6063733694724"></a><a name="p6063733694724"></a>-</p>
</td>
</tr>
<tr id="row5915532120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p16259111716216"><a name="p16259111716216"></a><a name="p16259111716216"></a>88</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4698609494724"><a name="p4698609494724"></a><a name="p4698609494724"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4777723694724"><a name="p4777723694724"></a><a name="p4777723694724"></a>Update Image Tag Definition</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4475090794724"><a name="p4475090794724"></a><a name="p4475090794724"></a>glance image-tag-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p94484294724"><a name="p94484294724"></a><a name="p94484294724"></a>-</p>
</td>
</tr>
<tr id="row4952668720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1625913174216"><a name="p1625913174216"></a><a name="p1625913174216"></a>89</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1770176094724"><a name="p1770176094724"></a><a name="p1770176094724"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2455644494724"><a name="p2455644494724"></a><a name="p2455644494724"></a>Delete Image Tag Definition</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4291490894724"><a name="p4291490894724"></a><a name="p4291490894724"></a>glance image-tag-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5355549694724"><a name="p5355549694724"></a><a name="p5355549694724"></a>-</p>
</td>
</tr>
<tr id="row4157105420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p625921715214"><a name="p625921715214"></a><a name="p625921715214"></a>90</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5170719394724"><a name="p5170719394724"></a><a name="p5170719394724"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2753312494724"><a name="p2753312494724"></a><a name="p2753312494724"></a>Create Image Metadata</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1559058494724"><a name="p1559058494724"></a><a name="p1559058494724"></a>glance image-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5487775594724"><a name="p5487775594724"></a><a name="p5487775594724"></a>Constraint:  You can set the value of the disk-format parameter to vhd instead of other values, such as raw.   The value of the --min-disk parameter must be greater than or equal to the disk size (in GB) indicated by the image file.</p>
</td>
</tr>
<tr id="row722814920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1425917178211"><a name="p1425917178211"></a><a name="p1425917178211"></a>91</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p900114794724"><a name="p900114794724"></a><a name="p900114794724"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5800428794724"><a name="p5800428794724"></a><a name="p5800428794724"></a>Upload Image File</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p72680094724"><a name="p72680094724"></a><a name="p72680094724"></a>glance image-upload</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5887080594724"><a name="p5887080594724"></a><a name="p5887080594724"></a>Constraint: The supported formats must be qcow2, vmdk, and vhd instead of other formats, such as zvhd.</p>
</td>
</tr>
<tr id="row2023200520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p72597171123"><a name="p72597171123"></a><a name="p72597171123"></a>92</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3425290994724"><a name="p3425290994724"></a><a name="p3425290994724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2302227794724"><a name="p2302227794724"></a><a name="p2302227794724"></a>Create Port</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5286513394724"><a name="p5286513394724"></a><a name="p5286513394724"></a>neutron port-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5421735794724"><a name="p5421735794724"></a><a name="p5421735794724"></a>The admin_state_up attribute can only be true.   The fixed_ip attribute contains only one port and a fixed IP address.     device_owner is read-only.   security_groups supports only one security group.</p>
</td>
</tr>
<tr id="row6384471720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1025914170216"><a name="p1025914170216"></a><a name="p1025914170216"></a>93</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6444166694724"><a name="p6444166694724"></a><a name="p6444166694724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5239247194724"><a name="p5239247194724"></a><a name="p5239247194724"></a>Update Port</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1593174494724"><a name="p1593174494724"></a><a name="p1593174494724"></a>neutron port-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1540288694724"><a name="p1540288694724"></a><a name="p1540288694724"></a>The admin_state_up attribute can only be true.   The fixed_ip attribute contains only one port and a fixed IP address.     device_owner is read-only.   security_groups supports only one security group.</p>
</td>
</tr>
<tr id="row3205247720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p925951710216"><a name="p925951710216"></a><a name="p925951710216"></a>94</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2152369894724"><a name="p2152369894724"></a><a name="p2152369894724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6569798294724"><a name="p6569798294724"></a><a name="p6569798294724"></a>Delete Port</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1993632294724"><a name="p1993632294724"></a><a name="p1993632294724"></a>neutron port-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p422941594724"><a name="p422941594724"></a><a name="p422941594724"></a>The admin_state_up attribute can only be true.   The fixed_ip attribute contains only one port and a fixed IP address.     device_owner is read-only.   security_groups supports only one security group.</p>
</td>
</tr>
<tr id="row810995920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1125914171222"><a name="p1125914171222"></a><a name="p1125914171222"></a>95</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6334521494724"><a name="p6334521494724"></a><a name="p6334521494724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3068871594724"><a name="p3068871594724"></a><a name="p3068871594724"></a>List Ports</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p275800594724"><a name="p275800594724"></a><a name="p275800594724"></a>neutron port-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2207184394724"><a name="p2207184394724"></a><a name="p2207184394724"></a>The admin_state_up attribute can only be true.   The fixed_ip attribute contains only one port and a fixed IP address.     device_owner is read-only.   security_groups supports only one security group.</p>
</td>
</tr>
<tr id="row4806087320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p2259111714219"><a name="p2259111714219"></a><a name="p2259111714219"></a>96</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5135543994724"><a name="p5135543994724"></a><a name="p5135543994724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6614991294724"><a name="p6614991294724"></a><a name="p6614991294724"></a>Show port Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5654262594724"><a name="p5654262594724"></a><a name="p5654262594724"></a>neutron port-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1654987494724"><a name="p1654987494724"></a><a name="p1654987494724"></a>The admin_state_up attribute can only be true.   The fixed_ip attribute contains only one port and a fixed IP address.     device_owner is read-only.   security_groups supports only one security group.</p>
</td>
</tr>
<tr id="row6623099920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p11259101717218"><a name="p11259101717218"></a><a name="p11259101717218"></a>97</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5237179894724"><a name="p5237179894724"></a><a name="p5237179894724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1425728494724"><a name="p1425728494724"></a><a name="p1425728494724"></a>List Networks</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1398936694724"><a name="p1398936694724"></a><a name="p1398936694724"></a>neutron net-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5939688594724"><a name="p5939688594724"></a><a name="p5939688594724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of shared.   provider:network_type supports only VXLAN.</p>
</td>
</tr>
<tr id="row4717616320253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p625913171126"><a name="p625913171126"></a><a name="p625913171126"></a>98</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1511220594724"><a name="p1511220594724"></a><a name="p1511220594724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1612908294724"><a name="p1612908294724"></a><a name="p1612908294724"></a>Show network Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3138724794724"><a name="p3138724794724"></a><a name="p3138724794724"></a>neutron net-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5933909394724"><a name="p5933909394724"></a><a name="p5933909394724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of shared.   provider:network_type supports only VXLAN.</p>
</td>
</tr>
<tr id="row672156220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p162597171622"><a name="p162597171622"></a><a name="p162597171622"></a>99</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4009080394724"><a name="p4009080394724"></a><a name="p4009080394724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2612964294724"><a name="p2612964294724"></a><a name="p2612964294724"></a>Create network</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3612622094724"><a name="p3612622094724"></a><a name="p3612622094724"></a>neutron net-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4054272394724"><a name="p4054272394724"></a><a name="p4054272394724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of shared.   provider:network_type supports only VXLAN.</p>
</td>
</tr>
<tr id="row3015287820253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p7259141715220"><a name="p7259141715220"></a><a name="p7259141715220"></a>100</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2774552394724"><a name="p2774552394724"></a><a name="p2774552394724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p3279489294724"><a name="p3279489294724"></a><a name="p3279489294724"></a>Update network</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3914063094724"><a name="p3914063094724"></a><a name="p3914063094724"></a>neutron net-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1627448994724"><a name="p1627448994724"></a><a name="p1627448994724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of shared.   provider:network_type supports only VXLAN.</p>
</td>
</tr>
<tr id="row1313607920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p225913171229"><a name="p225913171229"></a><a name="p225913171229"></a>101</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5294258994724"><a name="p5294258994724"></a><a name="p5294258994724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6049129994724"><a name="p6049129994724"></a><a name="p6049129994724"></a>Delete network</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p84822394724"><a name="p84822394724"></a><a name="p84822394724"></a>neutron net-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p159720694724"><a name="p159720694724"></a><a name="p159720694724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of shared.   provider:network_type supports only VXLAN.</p>
</td>
</tr>
<tr id="row2811281220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1325913171026"><a name="p1325913171026"></a><a name="p1325913171026"></a>102</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p2351303494724"><a name="p2351303494724"></a><a name="p2351303494724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2550757694724"><a name="p2550757694724"></a><a name="p2550757694724"></a>List subnets</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5284774294724"><a name="p5284774294724"></a><a name="p5284774294724"></a>neutron subnet-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5280870994724"><a name="p5280870994724"></a><a name="p5280870994724"></a>IPv6 is not supported.</p>
</td>
</tr>
<tr id="row2432575020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1625901711211"><a name="p1625901711211"></a><a name="p1625901711211"></a>103</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4417007594724"><a name="p4417007594724"></a><a name="p4417007594724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2100629894724"><a name="p2100629894724"></a><a name="p2100629894724"></a>Show subnet Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2378856694724"><a name="p2378856694724"></a><a name="p2378856694724"></a>neutron subnet-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4782565494724"><a name="p4782565494724"></a><a name="p4782565494724"></a>IPv6 is not supported.</p>
</td>
</tr>
<tr id="row5265622020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p62591617729"><a name="p62591617729"></a><a name="p62591617729"></a>104</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3540146594724"><a name="p3540146594724"></a><a name="p3540146594724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4894640394724"><a name="p4894640394724"></a><a name="p4894640394724"></a>Create subnet</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p523572694724"><a name="p523572694724"></a><a name="p523572694724"></a>neutron subnet-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p2144067494724"><a name="p2144067494724"></a><a name="p2144067494724"></a>IPv6 is not supported.</p>
</td>
</tr>
<tr id="row5897281520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p11259151719210"><a name="p11259151719210"></a><a name="p11259151719210"></a>105</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6099493394724"><a name="p6099493394724"></a><a name="p6099493394724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4164254994724"><a name="p4164254994724"></a><a name="p4164254994724"></a>Update subnet</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1760328994724"><a name="p1760328994724"></a><a name="p1760328994724"></a>neutron subnet-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1658029894724"><a name="p1658029894724"></a><a name="p1658029894724"></a>IPv6 is not supported.</p>
</td>
</tr>
<tr id="row3452012620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p102590171526"><a name="p102590171526"></a><a name="p102590171526"></a>106</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p744176894724"><a name="p744176894724"></a><a name="p744176894724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6591237594724"><a name="p6591237594724"></a><a name="p6591237594724"></a>Delete subnet</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3730219194724"><a name="p3730219194724"></a><a name="p3730219194724"></a>neutron subnet-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p157861594724"><a name="p157861594724"></a><a name="p157861594724"></a>IPv6 is not supported.</p>
</td>
</tr>
<tr id="row3680834620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1225921711211"><a name="p1225921711211"></a><a name="p1225921711211"></a>107</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p995979694724"><a name="p995979694724"></a><a name="p995979694724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p143714894724"><a name="p143714894724"></a><a name="p143714894724"></a>List routers</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4930017794724"><a name="p4930017794724"></a><a name="p4930017794724"></a>neutron router-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3389138694724"><a name="p3389138694724"></a><a name="p3389138694724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row6422651420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p9259417729"><a name="p9259417729"></a><a name="p9259417729"></a>108</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1075878594724"><a name="p1075878594724"></a><a name="p1075878594724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6615522894724"><a name="p6615522894724"></a><a name="p6615522894724"></a>Show router Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5697325694724"><a name="p5697325694724"></a><a name="p5697325694724"></a>neutron router-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5143102094724"><a name="p5143102094724"></a><a name="p5143102094724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row3603765520253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p72597171227"><a name="p72597171227"></a><a name="p72597171227"></a>109</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4646809594724"><a name="p4646809594724"></a><a name="p4646809594724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p581938494724"><a name="p581938494724"></a><a name="p581938494724"></a>Create router</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p160810194724"><a name="p160810194724"></a><a name="p160810194724"></a>neutron router-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6314737594724"><a name="p6314737594724"></a><a name="p6314737594724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row6230517620253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1625921718211"><a name="p1625921718211"></a><a name="p1625921718211"></a>110</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6486480994724"><a name="p6486480994724"></a><a name="p6486480994724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1955820194724"><a name="p1955820194724"></a><a name="p1955820194724"></a>Update router</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4071046694724"><a name="p4071046694724"></a><a name="p4071046694724"></a>neutron router-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p921341994724"><a name="p921341994724"></a><a name="p921341994724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row4744922120253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1926016171024"><a name="p1926016171024"></a><a name="p1926016171024"></a>111</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p569606394724"><a name="p569606394724"></a><a name="p569606394724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5872798494724"><a name="p5872798494724"></a><a name="p5872798494724"></a>Delete router</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5934630294724"><a name="p5934630294724"></a><a name="p5934630294724"></a>neutron router-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4232116894724"><a name="p4232116894724"></a><a name="p4232116894724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row1994190420253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p20260151717212"><a name="p20260151717212"></a><a name="p20260151717212"></a>112</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4916346694724"><a name="p4916346694724"></a><a name="p4916346694724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2281784794724"><a name="p2281784794724"></a><a name="p2281784794724"></a>List router ports</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3630630894724"><a name="p3630630894724"></a><a name="p3630630894724"></a>neutron router-port-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5512981794724"><a name="p5512981794724"></a><a name="p5512981794724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row3051351020253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p726015177215"><a name="p726015177215"></a><a name="p726015177215"></a>113</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5853641294724"><a name="p5853641294724"></a><a name="p5853641294724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4382890994724"><a name="p4382890994724"></a><a name="p4382890994724"></a>Add router interface</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6048077294724"><a name="p6048077294724"></a><a name="p6048077294724"></a>neutron router-interface-add</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p6710432694724"><a name="p6710432694724"></a><a name="p6710432694724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row474565720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p42604174212"><a name="p42604174212"></a><a name="p42604174212"></a>114</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6380116494724"><a name="p6380116494724"></a><a name="p6380116494724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p51180594724"><a name="p51180594724"></a><a name="p51180594724"></a>Delete router interface</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4145624694724"><a name="p4145624694724"></a><a name="p4145624694724"></a>neutron router-interface-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p251280094724"><a name="p251280094724"></a><a name="p251280094724"></a>The admin_state_up attribute can only be true.   Only the tenant who has the administrator right can set the value of distributed.   Only the tenant who has the administrator right can set the value of ha.</p>
</td>
</tr>
<tr id="row303621720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1626021719218"><a name="p1626021719218"></a><a name="p1626021719218"></a>115</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1989247794724"><a name="p1989247794724"></a><a name="p1989247794724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p67791194724"><a name="p67791194724"></a><a name="p67791194724"></a>List floating IPs</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5491081394724"><a name="p5491081394724"></a><a name="p5491081394724"></a>neutron floatingip-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p1859090594724"><a name="p1859090594724"></a><a name="p1859090594724"></a>floating_network_id supports only fixed external networks.</p>
</td>
</tr>
<tr id="row6585243720253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1526021713216"><a name="p1526021713216"></a><a name="p1526021713216"></a>116</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p6388815094724"><a name="p6388815094724"></a><a name="p6388815094724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p755768494724"><a name="p755768494724"></a><a name="p755768494724"></a>Show floating IP Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p819264294724"><a name="p819264294724"></a><a name="p819264294724"></a>neutron floatingip-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5962423294724"><a name="p5962423294724"></a><a name="p5962423294724"></a>floating_network_id supports only fixed external networks.</p>
</td>
</tr>
<tr id="row3014822220253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p4260151716211"><a name="p4260151716211"></a><a name="p4260151716211"></a>117</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4663047494724"><a name="p4663047494724"></a><a name="p4663047494724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1897205394724"><a name="p1897205394724"></a><a name="p1897205394724"></a>Create floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6034130094724"><a name="p6034130094724"></a><a name="p6034130094724"></a>neutron floatingip-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5580712094724"><a name="p5580712094724"></a><a name="p5580712094724"></a>floating_network_id supports only fixed external networks.</p>
</td>
</tr>
<tr id="row3836585920253"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p6260191717213"><a name="p6260191717213"></a><a name="p6260191717213"></a>118</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1541889794724"><a name="p1541889794724"></a><a name="p1541889794724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4097113994724"><a name="p4097113994724"></a><a name="p4097113994724"></a>Associate floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3032794994724"><a name="p3032794994724"></a><a name="p3032794994724"></a>neutron floatingip-associate</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4064482494724"><a name="p4064482494724"></a><a name="p4064482494724"></a>floating_network_id supports only fixed external networks.</p>
</td>
</tr>
<tr id="row4631005294523"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1526081713214"><a name="p1526081713214"></a><a name="p1526081713214"></a>119</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3506814094724"><a name="p3506814094724"></a><a name="p3506814094724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2194708794724"><a name="p2194708794724"></a><a name="p2194708794724"></a>Delete floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3288363194724"><a name="p3288363194724"></a><a name="p3288363194724"></a>neutron floatingip-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4632843594724"><a name="p4632843594724"></a><a name="p4632843594724"></a>floating_network_id supports only fixed external networks.</p>
</td>
</tr>
<tr id="row4020080094532"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p626020171821"><a name="p626020171821"></a><a name="p626020171821"></a>120</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1767082094724"><a name="p1767082094724"></a><a name="p1767082094724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2205032294724"><a name="p2205032294724"></a><a name="p2205032294724"></a>Disassociate floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4124569794724"><a name="p4124569794724"></a><a name="p4124569794724"></a>neutron floatingip-disassociate</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5256719394724"><a name="p5256719394724"></a><a name="p5256719394724"></a>floating_network_id supports only fixed external networks.</p>
</td>
</tr>
<tr id="row2461396494539"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1626019172212"><a name="p1626019172212"></a><a name="p1626019172212"></a>121</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p232257094724"><a name="p232257094724"></a><a name="p232257094724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p5391051094724"><a name="p5391051094724"></a><a name="p5391051094724"></a>List security groups</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p467519094724"><a name="p467519094724"></a><a name="p467519094724"></a>neutron security-group-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4314612394724"><a name="p4314612394724"></a><a name="p4314612394724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row2143776394539"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p202601317423"><a name="p202601317423"></a><a name="p202601317423"></a>122</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p4657554494724"><a name="p4657554494724"></a><a name="p4657554494724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1452269994724"><a name="p1452269994724"></a><a name="p1452269994724"></a>Show security group Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p3548794294724"><a name="p3548794294724"></a><a name="p3548794294724"></a>neutron security-group-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p5595105894724"><a name="p5595105894724"></a><a name="p5595105894724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row6371440194546"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p62601017329"><a name="p62601017329"></a><a name="p62601017329"></a>123</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5324116594724"><a name="p5324116594724"></a><a name="p5324116594724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1756712994724"><a name="p1756712994724"></a><a name="p1756712994724"></a>Create security group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1365137894724"><a name="p1365137894724"></a><a name="p1365137894724"></a>neutron security-group-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3201983994724"><a name="p3201983994724"></a><a name="p3201983994724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row4953792094546"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p152603175216"><a name="p152603175216"></a><a name="p152603175216"></a>124</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p5568734894724"><a name="p5568734894724"></a><a name="p5568734894724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p1438133194724"><a name="p1438133194724"></a><a name="p1438133194724"></a>Update security group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2403718794724"><a name="p2403718794724"></a><a name="p2403718794724"></a>neutron security-group-update</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p85514894724"><a name="p85514894724"></a><a name="p85514894724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row2165690694546"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p142601817922"><a name="p142601817922"></a><a name="p142601817922"></a>125</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p1942319794724"><a name="p1942319794724"></a><a name="p1942319794724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2977509794724"><a name="p2977509794724"></a><a name="p2977509794724"></a>Delete security group</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p6297268294724"><a name="p6297268294724"></a><a name="p6297268294724"></a>neutron security-group-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p51365694724"><a name="p51365694724"></a><a name="p51365694724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row1661260494546"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p626010177219"><a name="p626010177219"></a><a name="p626010177219"></a>126</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p3891136194724"><a name="p3891136194724"></a><a name="p3891136194724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p6481250094724"><a name="p6481250094724"></a><a name="p6481250094724"></a>List security group rules</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p1532118594724"><a name="p1532118594724"></a><a name="p1532118594724"></a>neutron security-group-rule-list</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p3305646294724"><a name="p3305646294724"></a><a name="p3305646294724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row4022572994554"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p172605171920"><a name="p172605171920"></a><a name="p172605171920"></a>127</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p607881794724"><a name="p607881794724"></a><a name="p607881794724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p2262213494724"><a name="p2262213494724"></a><a name="p2262213494724"></a>Show security group rule Details</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p2045354394724"><a name="p2045354394724"></a><a name="p2045354394724"></a>neutron security-group-rule-show</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4612431894724"><a name="p4612431894724"></a><a name="p4612431894724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row3224541494554"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1726061715220"><a name="p1726061715220"></a><a name="p1726061715220"></a>128</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p308698294724"><a name="p308698294724"></a><a name="p308698294724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4871896694724"><a name="p4871896694724"></a><a name="p4871896694724"></a>Create security group rule</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p5392218394724"><a name="p5392218394724"></a><a name="p5392218394724"></a>neutron security-group-rule-create</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p562070494724"><a name="p562070494724"></a><a name="p562070494724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
<tr id="row887772994554"><td class="cellrowborder" valign="top" width="8.43%" headers="mcps1.1.6.1.1 "><p id="p1826091711216"><a name="p1826091711216"></a><a name="p1826091711216"></a>129</p>
</td>
<td class="cellrowborder" valign="top" width="15.409999999999998%" headers="mcps1.1.6.1.2 "><p id="p385318594724"><a name="p385318594724"></a><a name="p385318594724"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="31.36%" headers="mcps1.1.6.1.3 "><p id="p4367256794724"><a name="p4367256794724"></a><a name="p4367256794724"></a>Delete security group rule</p>
</td>
<td class="cellrowborder" valign="top" width="24.9%" headers="mcps1.1.6.1.4 "><p id="p4781700994724"><a name="p4781700994724"></a><a name="p4781700994724"></a>neutron security-group-rule-delete</p>
</td>
<td class="cellrowborder" valign="top" width="19.900000000000002%" headers="mcps1.1.6.1.5 "><p id="p4797250394724"><a name="p4797250394724"></a><a name="p4797250394724"></a>You cannot set the name field to default when creating and updating the field.   Ethertype does not support IPv6.</p>
</td>
</tr>
</tbody>
</table>

## OpenStack Unified CLI<a name="section4552338120253"></a>

<a name="table4862053220253"></a>
<table><thead align="left"><tr id="row1379072620253"><th class="cellrowborder" valign="top" width="8.08080808080808%" id="mcps1.1.6.1.1"><p id="p085219156316"><a name="p085219156316"></a><a name="p085219156316"></a>序号</p>
</th>
<th class="cellrowborder" valign="top" width="19.19191919191919%" id="mcps1.1.6.1.2"><p id="p1403317920253"><a name="p1403317920253"></a><a name="p1403317920253"></a>组件</p>
</th>
<th class="cellrowborder" valign="top" width="22.222222222222225%" id="mcps1.1.6.1.3"><p id="p4842084120253"><a name="p4842084120253"></a><a name="p4842084120253"></a>功能</p>
</th>
<th class="cellrowborder" valign="top" width="33.33333333333333%" id="mcps1.1.6.1.4"><p id="p4983813720253"><a name="p4983813720253"></a><a name="p4983813720253"></a>命令行</p>
</th>
<th class="cellrowborder" valign="top" width="17.17171717171717%" id="mcps1.1.6.1.5"><p id="p4976909820253"><a name="p4976909820253"></a><a name="p4976909820253"></a>备注</p>
</th>
</tr>
</thead>
<tbody><tr id="row4169507020253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p108527159318"><a name="p108527159318"></a><a name="p108527159318"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p48146654205412"><a name="p48146654205412"></a><a name="p48146654205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p19683575205412"><a name="p19683575205412"></a><a name="p19683575205412"></a>List Servers</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p27686291205412"><a name="p27686291205412"></a><a name="p27686291205412"></a>openstack server list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p18491184205412"><a name="p18491184205412"></a><a name="p18491184205412"></a>-</p>
</td>
</tr>
<tr id="row217966920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1485214151437"><a name="p1485214151437"></a><a name="p1485214151437"></a>2</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p5734488205412"><a name="p5734488205412"></a><a name="p5734488205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p3733931205412"><a name="p3733931205412"></a><a name="p3733931205412"></a>Show Server Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p39719359205412"><a name="p39719359205412"></a><a name="p39719359205412"></a>openstack server show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p36274454205412"><a name="p36274454205412"></a><a name="p36274454205412"></a>-</p>
</td>
</tr>
<tr id="row2549170420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p785481517312"><a name="p785481517312"></a><a name="p785481517312"></a>3</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p5383691205412"><a name="p5383691205412"></a><a name="p5383691205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p24369335205412"><a name="p24369335205412"></a><a name="p24369335205412"></a>Update Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p30205028205412"><a name="p30205028205412"></a><a name="p30205028205412"></a>openstack server set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p9933204205412"><a name="p9933204205412"></a><a name="p9933204205412"></a>Constraint:  Only the VM name can be updated.</p>
</td>
</tr>
<tr id="row5471602520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p18541157310"><a name="p18541157310"></a><a name="p18541157310"></a>4</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p17523079205412"><a name="p17523079205412"></a><a name="p17523079205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p23716268205412"><a name="p23716268205412"></a><a name="p23716268205412"></a>Delete Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p57212178205412"><a name="p57212178205412"></a><a name="p57212178205412"></a>openstack server delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p131591218132715"><a name="p131591218132715"></a><a name="p131591218132715"></a>-</p>
</td>
</tr>
<tr id="row702669320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p385431512319"><a name="p385431512319"></a><a name="p385431512319"></a>5</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p16874587205412"><a name="p16874587205412"></a><a name="p16874587205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p55706137205412"><a name="p55706137205412"></a><a name="p55706137205412"></a>Resize Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p64679256205412"><a name="p64679256205412"></a><a name="p64679256205412"></a>openstack server resize --flavor</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p15380151813272"><a name="p15380151813272"></a><a name="p15380151813272"></a>-</p>
</td>
</tr>
<tr id="row5200199820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p128542154315"><a name="p128542154315"></a><a name="p128542154315"></a>6</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p29786648205412"><a name="p29786648205412"></a><a name="p29786648205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p24078734205412"><a name="p24078734205412"></a><a name="p24078734205412"></a>Confirm Resized Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p49285319205412"><a name="p49285319205412"></a><a name="p49285319205412"></a>openstack server resize --confirm</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p6600181892712"><a name="p6600181892712"></a><a name="p6600181892712"></a>-</p>
</td>
</tr>
<tr id="row2224282020253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p285431511311"><a name="p285431511311"></a><a name="p285431511311"></a>7</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p56262733205412"><a name="p56262733205412"></a><a name="p56262733205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p66832797205412"><a name="p66832797205412"></a><a name="p66832797205412"></a>Revert Resized Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p34907374205412"><a name="p34907374205412"></a><a name="p34907374205412"></a>openstack server resize --revert</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p582261814276"><a name="p582261814276"></a><a name="p582261814276"></a>-</p>
</td>
</tr>
<tr id="row1989192620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p15854131519314"><a name="p15854131519314"></a><a name="p15854131519314"></a>8</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p17680011205412"><a name="p17680011205412"></a><a name="p17680011205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p60397011205412"><a name="p60397011205412"></a><a name="p60397011205412"></a>List Flavors</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p5658974205412"><a name="p5658974205412"></a><a name="p5658974205412"></a>openstack flavor list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p124331942711"><a name="p124331942711"></a><a name="p124331942711"></a>-</p>
</td>
</tr>
<tr id="row5479333320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p9854141516311"><a name="p9854141516311"></a><a name="p9854141516311"></a>9</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p15410785205412"><a name="p15410785205412"></a><a name="p15410785205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p5129154205412"><a name="p5129154205412"></a><a name="p5129154205412"></a>Show Flavor Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p15613862205412"><a name="p15613862205412"></a><a name="p15613862205412"></a>openstack flavor show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p4268141952716"><a name="p4268141952716"></a><a name="p4268141952716"></a>-</p>
</td>
</tr>
<tr id="row3969179220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p285415151633"><a name="p285415151633"></a><a name="p285415151633"></a>10</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p44708703205412"><a name="p44708703205412"></a><a name="p44708703205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p33852154205412"><a name="p33852154205412"></a><a name="p33852154205412"></a>Stop Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p22229846205412"><a name="p22229846205412"></a><a name="p22229846205412"></a>openstack server stop</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1550021942715"><a name="p1550021942715"></a><a name="p1550021942715"></a>-</p>
</td>
</tr>
<tr id="row5858632820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p285419159319"><a name="p285419159319"></a><a name="p285419159319"></a>11</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p53052183205412"><a name="p53052183205412"></a><a name="p53052183205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p60204298205412"><a name="p60204298205412"></a><a name="p60204298205412"></a>Start Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p64229888205412"><a name="p64229888205412"></a><a name="p64229888205412"></a>openstack server start</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1274011192275"><a name="p1274011192275"></a><a name="p1274011192275"></a>-</p>
</td>
</tr>
<tr id="row1904537220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p98542015331"><a name="p98542015331"></a><a name="p98542015331"></a>12</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p24177942205412"><a name="p24177942205412"></a><a name="p24177942205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p23104899205412"><a name="p23104899205412"></a><a name="p23104899205412"></a>Lock Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p62520113205412"><a name="p62520113205412"></a><a name="p62520113205412"></a>openstack server lock</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p149195357277"><a name="p149195357277"></a><a name="p149195357277"></a>-</p>
</td>
</tr>
<tr id="row1388356520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p13854141515319"><a name="p13854141515319"></a><a name="p13854141515319"></a>13</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p37473006205412"><a name="p37473006205412"></a><a name="p37473006205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p5915124205412"><a name="p5915124205412"></a><a name="p5915124205412"></a>Unlock Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p66228347205412"><a name="p66228347205412"></a><a name="p66228347205412"></a>openstack server unlock</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p7154113616273"><a name="p7154113616273"></a><a name="p7154113616273"></a>-</p>
</td>
</tr>
<tr id="row3324572220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p48549151632"><a name="p48549151632"></a><a name="p48549151632"></a>14</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p51066927205412"><a name="p51066927205412"></a><a name="p51066927205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p45744622205412"><a name="p45744622205412"></a><a name="p45744622205412"></a>Detach Volume</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p21116270205412"><a name="p21116270205412"></a><a name="p21116270205412"></a>openstack server remove volume</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p17398736112719"><a name="p17398736112719"></a><a name="p17398736112719"></a>-</p>
</td>
</tr>
<tr id="row1695371520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p11854615330"><a name="p11854615330"></a><a name="p11854615330"></a>15</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p29381224205412"><a name="p29381224205412"></a><a name="p29381224205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p52334336205412"><a name="p52334336205412"></a><a name="p52334336205412"></a>List Keypairs</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p16666521205412"><a name="p16666521205412"></a><a name="p16666521205412"></a>openstack keypair list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p156239364276"><a name="p156239364276"></a><a name="p156239364276"></a>-</p>
</td>
</tr>
<tr id="row2901245820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p16854131514312"><a name="p16854131514312"></a><a name="p16854131514312"></a>16</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p29260074205412"><a name="p29260074205412"></a><a name="p29260074205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p54619322205412"><a name="p54619322205412"></a><a name="p54619322205412"></a>Add Keypair</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p21989005205412"><a name="p21989005205412"></a><a name="p21989005205412"></a>openstack keypair create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1541723716272"><a name="p1541723716272"></a><a name="p1541723716272"></a>-</p>
</td>
</tr>
<tr id="row62686020253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p78541515439"><a name="p78541515439"></a><a name="p78541515439"></a>17</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p60132868205412"><a name="p60132868205412"></a><a name="p60132868205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p53551277205412"><a name="p53551277205412"></a><a name="p53551277205412"></a>Show Keypairs</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p66847705205412"><a name="p66847705205412"></a><a name="p66847705205412"></a>openstack keypair show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p176381037112711"><a name="p176381037112711"></a><a name="p176381037112711"></a>-</p>
</td>
</tr>
<tr id="row3158551620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p38541915639"><a name="p38541915639"></a><a name="p38541915639"></a>18</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p3421319205412"><a name="p3421319205412"></a><a name="p3421319205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p34828905205412"><a name="p34828905205412"></a><a name="p34828905205412"></a>Delete Keypair</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p12169998205412"><a name="p12169998205412"></a><a name="p12169998205412"></a>openstack keypair delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p15866163742716"><a name="p15866163742716"></a><a name="p15866163742716"></a>-</p>
</td>
</tr>
<tr id="row2527432720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p2085414151636"><a name="p2085414151636"></a><a name="p2085414151636"></a>19</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p10621506205412"><a name="p10621506205412"></a><a name="p10621506205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p24095613205412"><a name="p24095613205412"></a><a name="p24095613205412"></a>Create Image</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p557499205412"><a name="p557499205412"></a><a name="p557499205412"></a>openstack server image create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p484338172712"><a name="p484338172712"></a><a name="p484338172712"></a>-</p>
</td>
</tr>
<tr id="row4982902320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p98542157312"><a name="p98542157312"></a><a name="p98542157312"></a>20</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p54660805205412"><a name="p54660805205412"></a><a name="p54660805205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p55162205412"><a name="p55162205412"></a><a name="p55162205412"></a>Reboot Server Hard</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p60071792205412"><a name="p60071792205412"></a><a name="p60071792205412"></a>openstack server reboot --hard</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1972774716274"><a name="p1972774716274"></a><a name="p1972774716274"></a>-</p>
</td>
</tr>
<tr id="row6647205220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p0854161518319"><a name="p0854161518319"></a><a name="p0854161518319"></a>21</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p60593057205412"><a name="p60593057205412"></a><a name="p60593057205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p17826799205412"><a name="p17826799205412"></a><a name="p17826799205412"></a>Reboot Server Soft</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p18922943205412"><a name="p18922943205412"></a><a name="p18922943205412"></a>openstack server reboot --soft</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p196415475276"><a name="p196415475276"></a><a name="p196415475276"></a>-</p>
</td>
</tr>
<tr id="row1488960520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1385413151932"><a name="p1385413151932"></a><a name="p1385413151932"></a>22</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p28429414205412"><a name="p28429414205412"></a><a name="p28429414205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p22446189205412"><a name="p22446189205412"></a><a name="p22446189205412"></a>Create Server(old)</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p16273461205412"><a name="p16273461205412"></a><a name="p16273461205412"></a>openstack server create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p20196114819275"><a name="p20196114819275"></a><a name="p20196114819275"></a>-</p>
</td>
</tr>
<tr id="row3754496320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p88541515639"><a name="p88541515639"></a><a name="p88541515639"></a>23</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p30664355205412"><a name="p30664355205412"></a><a name="p30664355205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p40377987205412"><a name="p40377987205412"></a><a name="p40377987205412"></a>Resize Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p15322212205412"><a name="p15322212205412"></a><a name="p15322212205412"></a>openstack server resize</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p8439348122717"><a name="p8439348122717"></a><a name="p8439348122717"></a>-</p>
</td>
</tr>
<tr id="row2084457320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p128541615334"><a name="p128541615334"></a><a name="p128541615334"></a>24</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p34165225205412"><a name="p34165225205412"></a><a name="p34165225205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p27619777205412"><a name="p27619777205412"></a><a name="p27619777205412"></a>Rebuild Server</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p13167068205412"><a name="p13167068205412"></a><a name="p13167068205412"></a>openstack server rebuild</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p9685448112718"><a name="p9685448112718"></a><a name="p9685448112718"></a>-</p>
</td>
</tr>
<tr id="row4699238820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p3854131520318"><a name="p3854131520318"></a><a name="p3854131520318"></a>25</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p32964551205412"><a name="p32964551205412"></a><a name="p32964551205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p62263225205412"><a name="p62263225205412"></a><a name="p62263225205412"></a>List Server Group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p24699436205412"><a name="p24699436205412"></a><a name="p24699436205412"></a>openstack server group list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p4911204812271"><a name="p4911204812271"></a><a name="p4911204812271"></a>-</p>
</td>
</tr>
<tr id="row6203363920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p68545151318"><a name="p68545151318"></a><a name="p68545151318"></a>26</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p38970318205412"><a name="p38970318205412"></a><a name="p38970318205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p25874424205412"><a name="p25874424205412"></a><a name="p25874424205412"></a>Create Server Group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p58634469205412"><a name="p58634469205412"></a><a name="p58634469205412"></a>openstack server group create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1214054982716"><a name="p1214054982716"></a><a name="p1214054982716"></a>-</p>
</td>
</tr>
<tr id="row1837925520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1085451513312"><a name="p1085451513312"></a><a name="p1085451513312"></a>27</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p14480269205412"><a name="p14480269205412"></a><a name="p14480269205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p65539088205412"><a name="p65539088205412"></a><a name="p65539088205412"></a>Show Server Group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p35345302205412"><a name="p35345302205412"></a><a name="p35345302205412"></a>openstack server group show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p8375104982717"><a name="p8375104982717"></a><a name="p8375104982717"></a>-</p>
</td>
</tr>
<tr id="row527165120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p16854121513319"><a name="p16854121513319"></a><a name="p16854121513319"></a>28</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p31712916205412"><a name="p31712916205412"></a><a name="p31712916205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p41410449205412"><a name="p41410449205412"></a><a name="p41410449205412"></a>Delete Server Group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p65931728205412"><a name="p65931728205412"></a><a name="p65931728205412"></a>openstack server group delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1848220541276"><a name="p1848220541276"></a><a name="p1848220541276"></a>-</p>
</td>
</tr>
<tr id="row1487036320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p12854201519314"><a name="p12854201519314"></a><a name="p12854201519314"></a>29</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p5043829205412"><a name="p5043829205412"></a><a name="p5043829205412"></a>Nova</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p56911882205412"><a name="p56911882205412"></a><a name="p56911882205412"></a>Show Absolute Limits</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p35558690205412"><a name="p35558690205412"></a><a name="p35558690205412"></a>openstack limits show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p117081054192717"><a name="p117081054192717"></a><a name="p117081054192717"></a>-</p>
</td>
</tr>
<tr id="row6537780920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p2854121514314"><a name="p2854121514314"></a><a name="p2854121514314"></a>30</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p19357373205412"><a name="p19357373205412"></a><a name="p19357373205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p7996684205412"><a name="p7996684205412"></a><a name="p7996684205412"></a>Create Volume</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p51345692205412"><a name="p51345692205412"></a><a name="p51345692205412"></a>openstack volume create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1692525452711"><a name="p1692525452711"></a><a name="p1692525452711"></a>-</p>
</td>
</tr>
<tr id="row6044817820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1085411155317"><a name="p1085411155317"></a><a name="p1085411155317"></a>31</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p63331582205412"><a name="p63331582205412"></a><a name="p63331582205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p47290406205412"><a name="p47290406205412"></a><a name="p47290406205412"></a>List Volumes</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p26753871205412"><a name="p26753871205412"></a><a name="p26753871205412"></a>openstack volume list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1814275515275"><a name="p1814275515275"></a><a name="p1814275515275"></a>-</p>
</td>
</tr>
<tr id="row3919089620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p148541715337"><a name="p148541715337"></a><a name="p148541715337"></a>32</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p56848584205412"><a name="p56848584205412"></a><a name="p56848584205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p33735913205412"><a name="p33735913205412"></a><a name="p33735913205412"></a>Delete Volume</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p29860683205412"><a name="p29860683205412"></a><a name="p29860683205412"></a>openstack volume delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p15363185510274"><a name="p15363185510274"></a><a name="p15363185510274"></a>-</p>
</td>
</tr>
<tr id="row6179391520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p12854515832"><a name="p12854515832"></a><a name="p12854515832"></a>33</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p55090090205412"><a name="p55090090205412"></a><a name="p55090090205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p64893156205412"><a name="p64893156205412"></a><a name="p64893156205412"></a>Show Volume</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p3013279205412"><a name="p3013279205412"></a><a name="p3013279205412"></a>openstack volume show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p125701655152713"><a name="p125701655152713"></a><a name="p125701655152713"></a>-</p>
</td>
</tr>
<tr id="row4953395420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p285421510318"><a name="p285421510318"></a><a name="p285421510318"></a>34</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p42115381205412"><a name="p42115381205412"></a><a name="p42115381205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p28296103205412"><a name="p28296103205412"></a><a name="p28296103205412"></a>List Backups</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p11488476205412"><a name="p11488476205412"></a><a name="p11488476205412"></a>openstack volume backup list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p48678551277"><a name="p48678551277"></a><a name="p48678551277"></a>-</p>
</td>
</tr>
<tr id="row5459814720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p98541915531"><a name="p98541915531"></a><a name="p98541915531"></a>35</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p1787640205412"><a name="p1787640205412"></a><a name="p1787640205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p583363205412"><a name="p583363205412"></a><a name="p583363205412"></a>Show Backup Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p31303569205412"><a name="p31303569205412"></a><a name="p31303569205412"></a>openstack volume backup show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p95851656142713"><a name="p95851656142713"></a><a name="p95851656142713"></a>-</p>
</td>
</tr>
<tr id="row2944002520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p15854191518319"><a name="p15854191518319"></a><a name="p15854191518319"></a>36</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p14390404205412"><a name="p14390404205412"></a><a name="p14390404205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p34784712205412"><a name="p34784712205412"></a><a name="p34784712205412"></a>Delete Backup</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p31152719205412"><a name="p31152719205412"></a><a name="p31152719205412"></a>openstack volume backup delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p35334807205412"><a name="p35334807205412"></a><a name="p35334807205412"></a>-</p>
</td>
</tr>
<tr id="row1368874420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p178550151333"><a name="p178550151333"></a><a name="p178550151333"></a>37</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p60167016205412"><a name="p60167016205412"></a><a name="p60167016205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p23629381205412"><a name="p23629381205412"></a><a name="p23629381205412"></a>Extend Volume</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p29701797205412"><a name="p29701797205412"></a><a name="p29701797205412"></a>openstack volume set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p65893638205412"><a name="p65893638205412"></a><a name="p65893638205412"></a>Constraint:  Only the name, description, property, and size can be configured.</p>
</td>
</tr>
<tr id="row4070017220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1785511517315"><a name="p1785511517315"></a><a name="p1785511517315"></a>38</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p16322356205412"><a name="p16322356205412"></a><a name="p16322356205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p58306507205412"><a name="p58306507205412"></a><a name="p58306507205412"></a>List Volumes Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p10801187205412"><a name="p10801187205412"></a><a name="p10801187205412"></a>openstack volume list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p442317312281"><a name="p442317312281"></a><a name="p442317312281"></a>-</p>
</td>
</tr>
<tr id="row5351678720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1885551517319"><a name="p1885551517319"></a><a name="p1885551517319"></a>39</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p65590649205412"><a name="p65590649205412"></a><a name="p65590649205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p24386537205412"><a name="p24386537205412"></a><a name="p24386537205412"></a>List snapshots with details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p48938075205412"><a name="p48938075205412"></a><a name="p48938075205412"></a>openstack snapshot list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1063883182810"><a name="p1063883182810"></a><a name="p1063883182810"></a>-</p>
</td>
</tr>
<tr id="row1030567120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p985512151234"><a name="p985512151234"></a><a name="p985512151234"></a>40</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p56751559205412"><a name="p56751559205412"></a><a name="p56751559205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p62293552205412"><a name="p62293552205412"></a><a name="p62293552205412"></a>Show snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p57725658205412"><a name="p57725658205412"></a><a name="p57725658205412"></a>openstack snapshot show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p16857533283"><a name="p16857533283"></a><a name="p16857533283"></a>-</p>
</td>
</tr>
<tr id="row2885426320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p118559151531"><a name="p118559151531"></a><a name="p118559151531"></a>41</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p48464301205412"><a name="p48464301205412"></a><a name="p48464301205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p30057519205412"><a name="p30057519205412"></a><a name="p30057519205412"></a>Delete snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p50621746205412"><a name="p50621746205412"></a><a name="p50621746205412"></a>openstack snapshot delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p8692410282"><a name="p8692410282"></a><a name="p8692410282"></a>-</p>
</td>
</tr>
<tr id="row4008280420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p20855215632"><a name="p20855215632"></a><a name="p20855215632"></a>42</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p39931068205412"><a name="p39931068205412"></a><a name="p39931068205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p65498486205412"><a name="p65498486205412"></a><a name="p65498486205412"></a>Create snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p58238707205412"><a name="p58238707205412"></a><a name="p58238707205412"></a>openstack snapshot create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p8280154162817"><a name="p8280154162817"></a><a name="p8280154162817"></a>-</p>
</td>
</tr>
<tr id="row4958212520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1885512157315"><a name="p1885512157315"></a><a name="p1885512157315"></a>43</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p46017667205412"><a name="p46017667205412"></a><a name="p46017667205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p50027415205412"><a name="p50027415205412"></a><a name="p50027415205412"></a>Update snapshot</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p54566316205412"><a name="p54566316205412"></a><a name="p54566316205412"></a>openstack snapshot set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p184971413289"><a name="p184971413289"></a><a name="p184971413289"></a>-</p>
</td>
</tr>
<tr id="row121685120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p188557156312"><a name="p188557156312"></a><a name="p188557156312"></a>44</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p63846547205412"><a name="p63846547205412"></a><a name="p63846547205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p4106783205412"><a name="p4106783205412"></a><a name="p4106783205412"></a>Querying EVS disk types</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p43102446205412"><a name="p43102446205412"></a><a name="p43102446205412"></a>openstack volume type list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p67166492819"><a name="p67166492819"></a><a name="p67166492819"></a>-</p>
</td>
</tr>
<tr id="row2703123020253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p485514151138"><a name="p485514151138"></a><a name="p485514151138"></a>45</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p14748283205412"><a name="p14748283205412"></a><a name="p14748283205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p21862048205412"><a name="p21862048205412"></a><a name="p21862048205412"></a>Querying details about an EVS disk type</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p51233352205412"><a name="p51233352205412"></a><a name="p51233352205412"></a>openstack volume type show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p16935842281"><a name="p16935842281"></a><a name="p16935842281"></a>-</p>
</td>
</tr>
<tr id="row6295716920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p5855121511320"><a name="p5855121511320"></a><a name="p5855121511320"></a>46</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p13893067205412"><a name="p13893067205412"></a><a name="p13893067205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p30056618205412"><a name="p30056618205412"></a><a name="p30056618205412"></a>List Backups with details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p49640779205412"><a name="p49640779205412"></a><a name="p49640779205412"></a>openstack volume backup list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p36172845205412"><a name="p36172845205412"></a><a name="p36172845205412"></a>-</p>
</td>
</tr>
<tr id="row3913253520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p4855191518312"><a name="p4855191518312"></a><a name="p4855191518312"></a>47</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p44855317205412"><a name="p44855317205412"></a><a name="p44855317205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p59296204205412"><a name="p59296204205412"></a><a name="p59296204205412"></a>Delete backup</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p14839686205412"><a name="p14839686205412"></a><a name="p14839686205412"></a>openstack volume backup delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p54290881205412"><a name="p54290881205412"></a><a name="p54290881205412"></a>-</p>
</td>
</tr>
<tr id="row4923207420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p8855101515315"><a name="p8855101515315"></a><a name="p8855101515315"></a>48</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p62521574205412"><a name="p62521574205412"></a><a name="p62521574205412"></a>Cinder</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p37606807205412"><a name="p37606807205412"></a><a name="p37606807205412"></a>Restore backup</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p17406089205412"><a name="p17406089205412"></a><a name="p17406089205412"></a>openstack volume backup restore</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p30532158205412"><a name="p30532158205412"></a><a name="p30532158205412"></a>-</p>
</td>
</tr>
<tr id="row1637570520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p585519155310"><a name="p585519155310"></a><a name="p585519155310"></a>49</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p4248016205412"><a name="p4248016205412"></a><a name="p4248016205412"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p62687642205412"><a name="p62687642205412"></a><a name="p62687642205412"></a>Show Image Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p17127909205412"><a name="p17127909205412"></a><a name="p17127909205412"></a>openstack image show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p63138611205412"><a name="p63138611205412"></a><a name="p63138611205412"></a>-</p>
</td>
</tr>
<tr id="row859214920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p6855915639"><a name="p6855915639"></a><a name="p6855915639"></a>50</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p61589091205412"><a name="p61589091205412"></a><a name="p61589091205412"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p28765542205412"><a name="p28765542205412"></a><a name="p28765542205412"></a>List Images</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p52944682205412"><a name="p52944682205412"></a><a name="p52944682205412"></a>openstack image list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p10245169205412"><a name="p10245169205412"></a><a name="p10245169205412"></a>-</p>
</td>
</tr>
<tr id="row1871976820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p108555152316"><a name="p108555152316"></a><a name="p108555152316"></a>51</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p21414958205412"><a name="p21414958205412"></a><a name="p21414958205412"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p34114186205412"><a name="p34114186205412"></a><a name="p34114186205412"></a>Delete Image</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p39146983205412"><a name="p39146983205412"></a><a name="p39146983205412"></a>openstack image delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p16936647205412"><a name="p16936647205412"></a><a name="p16936647205412"></a>-</p>
</td>
</tr>
<tr id="row3548597020253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p785520158314"><a name="p785520158314"></a><a name="p785520158314"></a>52</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p42005186205412"><a name="p42005186205412"></a><a name="p42005186205412"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p42511510205412"><a name="p42511510205412"></a><a name="p42511510205412"></a>Update Image Tag Definition</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p57028013205412"><a name="p57028013205412"></a><a name="p57028013205412"></a>openstack image set  --tag</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p27807365205412"><a name="p27807365205412"></a><a name="p27807365205412"></a>Constraint:   The image whose status is queued cannot be configured with labels.</p>
</td>
</tr>
<tr id="row1912469720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p285511151331"><a name="p285511151331"></a><a name="p285511151331"></a>53</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p62323630205412"><a name="p62323630205412"></a><a name="p62323630205412"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p23372059205412"><a name="p23372059205412"></a><a name="p23372059205412"></a>Delete Image Tag Definition</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p17913867205412"><a name="p17913867205412"></a><a name="p17913867205412"></a>openstack image unset  --tag</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p46631165205412"><a name="p46631165205412"></a><a name="p46631165205412"></a>-</p>
</td>
</tr>
<tr id="row2732175620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p38558152039"><a name="p38558152039"></a><a name="p38558152039"></a>54</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p8735363205412"><a name="p8735363205412"></a><a name="p8735363205412"></a>Glance</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p50460585205412"><a name="p50460585205412"></a><a name="p50460585205412"></a>Create Image</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p56526994205412"><a name="p56526994205412"></a><a name="p56526994205412"></a>openstack image create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p19068348205412"><a name="p19068348205412"></a><a name="p19068348205412"></a>Constraint:  You can set the value of the disk-format parameter to vhd instead of other values, such as raw.   The value of the --min-disk parameter must be greater than or equal to the disk size (in GB) indicated by the image file.</p>
</td>
</tr>
<tr id="row5686699420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p38551115832"><a name="p38551115832"></a><a name="p38551115832"></a>55</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p10636496205412"><a name="p10636496205412"></a><a name="p10636496205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p40419791205412"><a name="p40419791205412"></a><a name="p40419791205412"></a>Create Port</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p60847313205412"><a name="p60847313205412"></a><a name="p60847313205412"></a>openstack port create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p26275412205412"><a name="p26275412205412"></a><a name="p26275412205412"></a>Constraint:  The device-owner, device, no-security-group, mac-address, and disable fields cannot be configured.</p>
</td>
</tr>
<tr id="row6548082320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p16855161514310"><a name="p16855161514310"></a><a name="p16855161514310"></a>56</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p37794341205412"><a name="p37794341205412"></a><a name="p37794341205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p20304670205412"><a name="p20304670205412"></a><a name="p20304670205412"></a>Update Port</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p32969816205412"><a name="p32969816205412"></a><a name="p32969816205412"></a>openstack port set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p888405205412"><a name="p888405205412"></a><a name="p888405205412"></a>Constraint:  The device-owner, device, no-security-group, and disable fields cannot be configured.</p>
</td>
</tr>
<tr id="row6560992520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p19855131513316"><a name="p19855131513316"></a><a name="p19855131513316"></a>57</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p49916948205412"><a name="p49916948205412"></a><a name="p49916948205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p1376549205412"><a name="p1376549205412"></a><a name="p1376549205412"></a>Delete Port</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p22667449205412"><a name="p22667449205412"></a><a name="p22667449205412"></a>openstack port delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p55898958205412"><a name="p55898958205412"></a><a name="p55898958205412"></a>-</p>
</td>
</tr>
<tr id="row4679656120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p20855101518312"><a name="p20855101518312"></a><a name="p20855101518312"></a>58</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p4140586205412"><a name="p4140586205412"></a><a name="p4140586205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p12804981205412"><a name="p12804981205412"></a><a name="p12804981205412"></a>List Ports</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p53089665205412"><a name="p53089665205412"></a><a name="p53089665205412"></a>openstack port list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p33914064205412"><a name="p33914064205412"></a><a name="p33914064205412"></a>-</p>
</td>
</tr>
<tr id="row3672794420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p185551512312"><a name="p185551512312"></a><a name="p185551512312"></a>59</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p5647865205412"><a name="p5647865205412"></a><a name="p5647865205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p43619229205412"><a name="p43619229205412"></a><a name="p43619229205412"></a>Show port</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p55373890205412"><a name="p55373890205412"></a><a name="p55373890205412"></a>openstack port show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p38407274205412"><a name="p38407274205412"></a><a name="p38407274205412"></a>-</p>
</td>
</tr>
<tr id="row1301410820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p17855615533"><a name="p17855615533"></a><a name="p17855615533"></a>60</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p14213905205412"><a name="p14213905205412"></a><a name="p14213905205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p43904301205412"><a name="p43904301205412"></a><a name="p43904301205412"></a>List Networks</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p30273676205412"><a name="p30273676205412"></a><a name="p30273676205412"></a>openstack network list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p17581485205412"><a name="p17581485205412"></a><a name="p17581485205412"></a>-</p>
</td>
</tr>
<tr id="row4676089320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p28553151439"><a name="p28553151439"></a><a name="p28553151439"></a>61</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p62981889205412"><a name="p62981889205412"></a><a name="p62981889205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p2018743205412"><a name="p2018743205412"></a><a name="p2018743205412"></a>Show network Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p50927598205412"><a name="p50927598205412"></a><a name="p50927598205412"></a>openstack network show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p28233256205412"><a name="p28233256205412"></a><a name="p28233256205412"></a>-</p>
</td>
</tr>
<tr id="row6498556220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p2855415334"><a name="p2855415334"></a><a name="p2855415334"></a>62</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p66721114205412"><a name="p66721114205412"></a><a name="p66721114205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p47502536205412"><a name="p47502536205412"></a><a name="p47502536205412"></a>Create network</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p56437241205412"><a name="p56437241205412"></a><a name="p56437241205412"></a>openstack network create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p55545195205412"><a name="p55545195205412"></a><a name="p55545195205412"></a>Constraint:  The share field cannot be configured.</p>
</td>
</tr>
<tr id="row2040419620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p15855171516313"><a name="p15855171516313"></a><a name="p15855171516313"></a>63</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p41651115205412"><a name="p41651115205412"></a><a name="p41651115205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p59581426205412"><a name="p59581426205412"></a><a name="p59581426205412"></a>Update network</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p57011260205412"><a name="p57011260205412"></a><a name="p57011260205412"></a>openstack network set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p9563399205412"><a name="p9563399205412"></a><a name="p9563399205412"></a>Constraint:  The share field cannot be configured.</p>
</td>
</tr>
<tr id="row4916045820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p15855141516312"><a name="p15855141516312"></a><a name="p15855141516312"></a>64</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p15411589205412"><a name="p15411589205412"></a><a name="p15411589205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p6004421205412"><a name="p6004421205412"></a><a name="p6004421205412"></a>Delete network</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p29255240205412"><a name="p29255240205412"></a><a name="p29255240205412"></a>openstack network delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p49354892205412"><a name="p49354892205412"></a><a name="p49354892205412"></a>-</p>
</td>
</tr>
<tr id="row6284761320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p585510151639"><a name="p585510151639"></a><a name="p585510151639"></a>65</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p46608503205412"><a name="p46608503205412"></a><a name="p46608503205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p22358736205412"><a name="p22358736205412"></a><a name="p22358736205412"></a>List subnets</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p55255468205412"><a name="p55255468205412"></a><a name="p55255468205412"></a>openstack subnet list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p43662729205412"><a name="p43662729205412"></a><a name="p43662729205412"></a>-</p>
</td>
</tr>
<tr id="row3311498820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p08558155317"><a name="p08558155317"></a><a name="p08558155317"></a>66</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p35169297205412"><a name="p35169297205412"></a><a name="p35169297205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p47312804205412"><a name="p47312804205412"></a><a name="p47312804205412"></a>Show subnet Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p51145208205412"><a name="p51145208205412"></a><a name="p51145208205412"></a>openstack subnet show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p63884175205412"><a name="p63884175205412"></a><a name="p63884175205412"></a>-</p>
</td>
</tr>
<tr id="row1255757620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p178551815137"><a name="p178551815137"></a><a name="p178551815137"></a>67</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p11373028205412"><a name="p11373028205412"></a><a name="p11373028205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p37197520205412"><a name="p37197520205412"></a><a name="p37197520205412"></a>Create subnet</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p41454781205412"><a name="p41454781205412"></a><a name="p41454781205412"></a>openstack subnet create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p47100973205412"><a name="p47100973205412"></a><a name="p47100973205412"></a>-</p>
</td>
</tr>
<tr id="row932928020253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p5855115536"><a name="p5855115536"></a><a name="p5855115536"></a>68</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p47917440205412"><a name="p47917440205412"></a><a name="p47917440205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p38505445205412"><a name="p38505445205412"></a><a name="p38505445205412"></a>Update subnet</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p56498571205412"><a name="p56498571205412"></a><a name="p56498571205412"></a>openstack subnet set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p55225076205412"><a name="p55225076205412"></a><a name="p55225076205412"></a>Constraint:  The host-route field cannot be configured.</p>
</td>
</tr>
<tr id="row3424691720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p8855171516319"><a name="p8855171516319"></a><a name="p8855171516319"></a>69</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p13126772205412"><a name="p13126772205412"></a><a name="p13126772205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p867442205412"><a name="p867442205412"></a><a name="p867442205412"></a>Delete subnet</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p5120497205412"><a name="p5120497205412"></a><a name="p5120497205412"></a>openstack subnet delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p6186355205412"><a name="p6186355205412"></a><a name="p6186355205412"></a>-</p>
</td>
</tr>
<tr id="row3517229420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p885514151535"><a name="p885514151535"></a><a name="p885514151535"></a>70</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p54492753205412"><a name="p54492753205412"></a><a name="p54492753205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p18372615205412"><a name="p18372615205412"></a><a name="p18372615205412"></a>List routers</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p9337216205412"><a name="p9337216205412"></a><a name="p9337216205412"></a>openstack router list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p34790202205412"><a name="p34790202205412"></a><a name="p34790202205412"></a>-</p>
</td>
</tr>
<tr id="row3743947520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1985691514311"><a name="p1985691514311"></a><a name="p1985691514311"></a>71</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p17386662205412"><a name="p17386662205412"></a><a name="p17386662205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p9375798205412"><a name="p9375798205412"></a><a name="p9375798205412"></a>Show router Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p9696711205412"><a name="p9696711205412"></a><a name="p9696711205412"></a>openstack router show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p23627227205412"><a name="p23627227205412"></a><a name="p23627227205412"></a>-</p>
</td>
</tr>
<tr id="row378796620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1685619152037"><a name="p1685619152037"></a><a name="p1685619152037"></a>72</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p30312196205412"><a name="p30312196205412"></a><a name="p30312196205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p59529356205412"><a name="p59529356205412"></a><a name="p59529356205412"></a>Create router</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p306775205412"><a name="p306775205412"></a><a name="p306775205412"></a>openstack router create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p65642723205412"><a name="p65642723205412"></a><a name="p65642723205412"></a>Constraint:  The ha, distributed, and disable fields cannot be configured.</p>
</td>
</tr>
<tr id="row100437220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1385611151731"><a name="p1385611151731"></a><a name="p1385611151731"></a>73</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p58883834205412"><a name="p58883834205412"></a><a name="p58883834205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p35530395205412"><a name="p35530395205412"></a><a name="p35530395205412"></a>Update router</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p37895359205412"><a name="p37895359205412"></a><a name="p37895359205412"></a>openstack router set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p63203812205412"><a name="p63203812205412"></a><a name="p63203812205412"></a>The disable field cannot be configured.</p>
</td>
</tr>
<tr id="row5251555920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p138565151333"><a name="p138565151333"></a><a name="p138565151333"></a>74</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p55920664205412"><a name="p55920664205412"></a><a name="p55920664205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p29864435205412"><a name="p29864435205412"></a><a name="p29864435205412"></a>Delete router</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p41680015205412"><a name="p41680015205412"></a><a name="p41680015205412"></a>openstack router delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p23945326205412"><a name="p23945326205412"></a><a name="p23945326205412"></a>-</p>
</td>
</tr>
<tr id="row6280925520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p785671515318"><a name="p785671515318"></a><a name="p785671515318"></a>75</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p53344240205412"><a name="p53344240205412"></a><a name="p53344240205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p42710051205412"><a name="p42710051205412"></a><a name="p42710051205412"></a>Add router interface</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p4803417205412"><a name="p4803417205412"></a><a name="p4803417205412"></a>openstack router add port</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p63538704205412"><a name="p63538704205412"></a><a name="p63538704205412"></a>-</p>
</td>
</tr>
<tr id="row6534035520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p15856181513316"><a name="p15856181513316"></a><a name="p15856181513316"></a>76</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p11331087205412"><a name="p11331087205412"></a><a name="p11331087205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p58632380205412"><a name="p58632380205412"></a><a name="p58632380205412"></a>Delete router interface</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p30132394205412"><a name="p30132394205412"></a><a name="p30132394205412"></a>openstack router remove port</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p65052251205412"><a name="p65052251205412"></a><a name="p65052251205412"></a>-</p>
</td>
</tr>
<tr id="row3894820420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p168568151137"><a name="p168568151137"></a><a name="p168568151137"></a>77</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p45476871205412"><a name="p45476871205412"></a><a name="p45476871205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p65080653205412"><a name="p65080653205412"></a><a name="p65080653205412"></a>List floating IPs</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p5871124205412"><a name="p5871124205412"></a><a name="p5871124205412"></a>openstack floating ip list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p18312926205412"><a name="p18312926205412"></a><a name="p18312926205412"></a>-</p>
</td>
</tr>
<tr id="row1420513720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p17856131518310"><a name="p17856131518310"></a><a name="p17856131518310"></a>78</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p42116456205412"><a name="p42116456205412"></a><a name="p42116456205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p29466983205412"><a name="p29466983205412"></a><a name="p29466983205412"></a>Show floating IP Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p11507495205412"><a name="p11507495205412"></a><a name="p11507495205412"></a>openstack floating ip show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p49413930205412"><a name="p49413930205412"></a><a name="p49413930205412"></a>-</p>
</td>
</tr>
<tr id="row5026589120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1985631513320"><a name="p1985631513320"></a><a name="p1985631513320"></a>79</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p20754369205412"><a name="p20754369205412"></a><a name="p20754369205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p52930201205412"><a name="p52930201205412"></a><a name="p52930201205412"></a>Create floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p61583730205412"><a name="p61583730205412"></a><a name="p61583730205412"></a>openstack floating ip create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p22927566205412"><a name="p22927566205412"></a><a name="p22927566205412"></a>-</p>
</td>
</tr>
<tr id="row6544065720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p128562154319"><a name="p128562154319"></a><a name="p128562154319"></a>80</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p52423331205412"><a name="p52423331205412"></a><a name="p52423331205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p46473331205412"><a name="p46473331205412"></a><a name="p46473331205412"></a>Associate floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p9374854205412"><a name="p9374854205412"></a><a name="p9374854205412"></a>openstack server add floating ip</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p8669018205412"><a name="p8669018205412"></a><a name="p8669018205412"></a>-</p>
</td>
</tr>
<tr id="row4158548420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1585611151137"><a name="p1585611151137"></a><a name="p1585611151137"></a>81</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p19183517205412"><a name="p19183517205412"></a><a name="p19183517205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p19993734205412"><a name="p19993734205412"></a><a name="p19993734205412"></a>Delete floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p29905394205412"><a name="p29905394205412"></a><a name="p29905394205412"></a>openstack floating ip delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p19175519205412"><a name="p19175519205412"></a><a name="p19175519205412"></a>-</p>
</td>
</tr>
<tr id="row4866189120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p985641516318"><a name="p985641516318"></a><a name="p985641516318"></a>82</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p36846144205412"><a name="p36846144205412"></a><a name="p36846144205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p61459042205412"><a name="p61459042205412"></a><a name="p61459042205412"></a>Disassociate floating IP</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p21359943205412"><a name="p21359943205412"></a><a name="p21359943205412"></a>openstack server remove floating ip</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p41311085205412"><a name="p41311085205412"></a><a name="p41311085205412"></a>-</p>
</td>
</tr>
<tr id="row557962220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1085691510320"><a name="p1085691510320"></a><a name="p1085691510320"></a>83</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p14194715205412"><a name="p14194715205412"></a><a name="p14194715205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p23006102205412"><a name="p23006102205412"></a><a name="p23006102205412"></a>List security groups</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p22039572205412"><a name="p22039572205412"></a><a name="p22039572205412"></a>openstack security group list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p43229715205412"><a name="p43229715205412"></a><a name="p43229715205412"></a>-</p>
</td>
</tr>
<tr id="row3296055120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p585691519312"><a name="p585691519312"></a><a name="p585691519312"></a>84</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p43202750205412"><a name="p43202750205412"></a><a name="p43202750205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p4481971205412"><a name="p4481971205412"></a><a name="p4481971205412"></a>Show security group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p49028585205412"><a name="p49028585205412"></a><a name="p49028585205412"></a>openstack security group show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p40583138205412"><a name="p40583138205412"></a><a name="p40583138205412"></a>-</p>
</td>
</tr>
<tr id="row3886923520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p3856515238"><a name="p3856515238"></a><a name="p3856515238"></a>85</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p26412474205412"><a name="p26412474205412"></a><a name="p26412474205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p40591432205412"><a name="p40591432205412"></a><a name="p40591432205412"></a>Create security group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p46437464205412"><a name="p46437464205412"></a><a name="p46437464205412"></a>openstack security group create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p37423721205412"><a name="p37423721205412"></a><a name="p37423721205412"></a>-</p>
</td>
</tr>
<tr id="row6423679620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p6856121515314"><a name="p6856121515314"></a><a name="p6856121515314"></a>86</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p34646687205412"><a name="p34646687205412"></a><a name="p34646687205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p15061222205412"><a name="p15061222205412"></a><a name="p15061222205412"></a>Update security group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p27108078205412"><a name="p27108078205412"></a><a name="p27108078205412"></a>openstack security group set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p59906361205412"><a name="p59906361205412"></a><a name="p59906361205412"></a>-</p>
</td>
</tr>
<tr id="row2902360220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p168561215639"><a name="p168561215639"></a><a name="p168561215639"></a>87</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p2544892205412"><a name="p2544892205412"></a><a name="p2544892205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p19924764205412"><a name="p19924764205412"></a><a name="p19924764205412"></a>Delete security group</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p21905213205412"><a name="p21905213205412"></a><a name="p21905213205412"></a>openstack security group delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p31131105205412"><a name="p31131105205412"></a><a name="p31131105205412"></a>-</p>
</td>
</tr>
<tr id="row319424420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p88567152316"><a name="p88567152316"></a><a name="p88567152316"></a>88</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p53769314205412"><a name="p53769314205412"></a><a name="p53769314205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p35853946205412"><a name="p35853946205412"></a><a name="p35853946205412"></a>List security group rules</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p54698197205412"><a name="p54698197205412"></a><a name="p54698197205412"></a>openstack security group rule list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p40774641205412"><a name="p40774641205412"></a><a name="p40774641205412"></a>-</p>
</td>
</tr>
<tr id="row4620349120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1185681518311"><a name="p1185681518311"></a><a name="p1185681518311"></a>89</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p63371872205412"><a name="p63371872205412"></a><a name="p63371872205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p24056978205412"><a name="p24056978205412"></a><a name="p24056978205412"></a>Show security group rule</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p25592133205412"><a name="p25592133205412"></a><a name="p25592133205412"></a>openstack security group rule show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p19654907205412"><a name="p19654907205412"></a><a name="p19654907205412"></a>-</p>
</td>
</tr>
<tr id="row86918220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p158569151038"><a name="p158569151038"></a><a name="p158569151038"></a>90</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p17603207205412"><a name="p17603207205412"></a><a name="p17603207205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p43866353205412"><a name="p43866353205412"></a><a name="p43866353205412"></a>Create security group rule</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p56056862205412"><a name="p56056862205412"></a><a name="p56056862205412"></a>openstack security group rule create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p43965580205412"><a name="p43965580205412"></a><a name="p43965580205412"></a>-</p>
</td>
</tr>
<tr id="row3016122220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1585617151435"><a name="p1585617151435"></a><a name="p1585617151435"></a>91</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p47090278205412"><a name="p47090278205412"></a><a name="p47090278205412"></a>Neutron</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p10140969205412"><a name="p10140969205412"></a><a name="p10140969205412"></a>Delete security group rule</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p37662447205412"><a name="p37662447205412"></a><a name="p37662447205412"></a>openstack security group rule delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p10889270205412"><a name="p10889270205412"></a><a name="p10889270205412"></a>-</p>
</td>
</tr>
<tr id="row108125820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p19856615036"><a name="p19856615036"></a><a name="p19856615036"></a>92</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p15942029205412"><a name="p15942029205412"></a><a name="p15942029205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p46783690205412"><a name="p46783690205412"></a><a name="p46783690205412"></a>Create new zone</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p11811145205412"><a name="p11811145205412"></a><a name="p11811145205412"></a>openstack zone create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p44543881205412"><a name="p44543881205412"></a><a name="p44543881205412"></a>-</p>
</td>
</tr>
<tr id="row4766607520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1385651515314"><a name="p1385651515314"></a><a name="p1385651515314"></a>93</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p25737614205412"><a name="p25737614205412"></a><a name="p25737614205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p43865443205412"><a name="p43865443205412"></a><a name="p43865443205412"></a>List Zones</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p55065787205412"><a name="p55065787205412"></a><a name="p55065787205412"></a>openstack zone list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p38426644205412"><a name="p38426644205412"></a><a name="p38426644205412"></a>-</p>
</td>
</tr>
<tr id="row1463610420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1485611152038"><a name="p1485611152038"></a><a name="p1485611152038"></a>94</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p39235062205412"><a name="p39235062205412"></a><a name="p39235062205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p45745797205412"><a name="p45745797205412"></a><a name="p45745797205412"></a>Show zone Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p22396117205412"><a name="p22396117205412"></a><a name="p22396117205412"></a>openstack zone show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p28854632205412"><a name="p28854632205412"></a><a name="p28854632205412"></a>-</p>
</td>
</tr>
<tr id="row4661321720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p585671517311"><a name="p585671517311"></a><a name="p585671517311"></a>95</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p49863767205412"><a name="p49863767205412"></a><a name="p49863767205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p10572223205412"><a name="p10572223205412"></a><a name="p10572223205412"></a>Delete zone</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p37535528205412"><a name="p37535528205412"></a><a name="p37535528205412"></a>openstack zone delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p6892820205412"><a name="p6892820205412"></a><a name="p6892820205412"></a>-</p>
</td>
</tr>
<tr id="row2442920820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p4856141517317"><a name="p4856141517317"></a><a name="p4856141517317"></a>96</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p8471617205412"><a name="p8471617205412"></a><a name="p8471617205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p31677090205412"><a name="p31677090205412"></a><a name="p31677090205412"></a>Create new recordset</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p2394948205412"><a name="p2394948205412"></a><a name="p2394948205412"></a>openstack recordset create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p57962153205412"><a name="p57962153205412"></a><a name="p57962153205412"></a>-</p>
</td>
</tr>
<tr id="row4634025020253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p6856815435"><a name="p6856815435"></a><a name="p6856815435"></a>97</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p60974915205412"><a name="p60974915205412"></a><a name="p60974915205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p31016637205412"><a name="p31016637205412"></a><a name="p31016637205412"></a>List Recordsets in a zone</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p21359288205412"><a name="p21359288205412"></a><a name="p21359288205412"></a>openstack recordset list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p40598454205412"><a name="p40598454205412"></a><a name="p40598454205412"></a>-</p>
</td>
</tr>
<tr id="row5832194620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p78561615134"><a name="p78561615134"></a><a name="p78561615134"></a>98</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p39946478205412"><a name="p39946478205412"></a><a name="p39946478205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p15170976205412"><a name="p15170976205412"></a><a name="p15170976205412"></a>Show recordset Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p12413205205412"><a name="p12413205205412"></a><a name="p12413205205412"></a>openstack recordset show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p29098955205412"><a name="p29098955205412"></a><a name="p29098955205412"></a>-</p>
</td>
</tr>
<tr id="row2595386120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p4856131514319"><a name="p4856131514319"></a><a name="p4856131514319"></a>99</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p38858449205412"><a name="p38858449205412"></a><a name="p38858449205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p38267100205412"><a name="p38267100205412"></a><a name="p38267100205412"></a>Delete recordset</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p65377258205412"><a name="p65377258205412"></a><a name="p65377258205412"></a>openstack recordset delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p60438650205412"><a name="p60438650205412"></a><a name="p60438650205412"></a>-</p>
</td>
</tr>
<tr id="row2713658920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p11856191510310"><a name="p11856191510310"></a><a name="p11856191510310"></a>100</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p5382269205412"><a name="p5382269205412"></a><a name="p5382269205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p22819841205412"><a name="p22819841205412"></a><a name="p22819841205412"></a>Set floatingip ptr record</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p20527816205412"><a name="p20527816205412"></a><a name="p20527816205412"></a>openstack ptr record set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p7540048205412"><a name="p7540048205412"></a><a name="p7540048205412"></a>-</p>
</td>
</tr>
<tr id="row4753750620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p385616152037"><a name="p385616152037"></a><a name="p385616152037"></a>101</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p48244609205412"><a name="p48244609205412"></a><a name="p48244609205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p59247774205412"><a name="p59247774205412"></a><a name="p59247774205412"></a>List floatingip ptr records</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p29208382205412"><a name="p29208382205412"></a><a name="p29208382205412"></a>openstack ptr record list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p65435615205412"><a name="p65435615205412"></a><a name="p65435615205412"></a>-</p>
</td>
</tr>
<tr id="row6596779520253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1585619151335"><a name="p1585619151335"></a><a name="p1585619151335"></a>102</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p65130349205412"><a name="p65130349205412"></a><a name="p65130349205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p59990596205412"><a name="p59990596205412"></a><a name="p59990596205412"></a>Unset floatingip ptr record</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p32834780205412"><a name="p32834780205412"></a><a name="p32834780205412"></a>openstack ptr record unset</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p55160759205412"><a name="p55160759205412"></a><a name="p55160759205412"></a>-</p>
</td>
</tr>
<tr id="row1026033720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p118561815331"><a name="p118561815331"></a><a name="p118561815331"></a>103</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p50587090205412"><a name="p50587090205412"></a><a name="p50587090205412"></a>DNS</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p60073602205412"><a name="p60073602205412"></a><a name="p60073602205412"></a>Show floatingip ptr record Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p56119604205412"><a name="p56119604205412"></a><a name="p56119604205412"></a>openstack ptr record show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p45182567205412"><a name="p45182567205412"></a><a name="p45182567205412"></a>-</p>
</td>
</tr>
<tr id="row3663329120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p78565151538"><a name="p78565151538"></a><a name="p78565151538"></a>104</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p26966592205412"><a name="p26966592205412"></a><a name="p26966592205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p40045801205412"><a name="p40045801205412"></a><a name="p40045801205412"></a>List services in the service catalog</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p56224723205412"><a name="p56224723205412"></a><a name="p56224723205412"></a>openstack catalog list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p25440128205412"><a name="p25440128205412"></a><a name="p25440128205412"></a>-</p>
</td>
</tr>
<tr id="row4202033820253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1285671510314"><a name="p1285671510314"></a><a name="p1285671510314"></a>105</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p17833542205412"><a name="p17833542205412"></a><a name="p17833542205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p26266376205412"><a name="p26266376205412"></a><a name="p26266376205412"></a>Display service catalog Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p15707723205412"><a name="p15707723205412"></a><a name="p15707723205412"></a>openstack catalog show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p60059793205412"><a name="p60059793205412"></a><a name="p60059793205412"></a>-</p>
</td>
</tr>
<tr id="row320309320253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p4856121514316"><a name="p4856121514316"></a><a name="p4856121514316"></a>106</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p13510005205412"><a name="p13510005205412"></a><a name="p13510005205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p15554671205412"><a name="p15554671205412"></a><a name="p15554671205412"></a>List endpoints</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p27604012205412"><a name="p27604012205412"></a><a name="p27604012205412"></a>openstack endpoint list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p63107371205412"><a name="p63107371205412"></a><a name="p63107371205412"></a>-</p>
</td>
</tr>
<tr id="row5222666120253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p15856121513318"><a name="p15856121513318"></a><a name="p15856121513318"></a>107</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p12641628205412"><a name="p12641628205412"></a><a name="p12641628205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p9416368205412"><a name="p9416368205412"></a><a name="p9416368205412"></a>Create new federation protocol</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p53877509205412"><a name="p53877509205412"></a><a name="p53877509205412"></a>openstack federation protocol create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p19460829205412"><a name="p19460829205412"></a><a name="p19460829205412"></a>-</p>
</td>
</tr>
<tr id="row288564920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p2085614156315"><a name="p2085614156315"></a><a name="p2085614156315"></a>108</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p22345100205412"><a name="p22345100205412"></a><a name="p22345100205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p40405336205412"><a name="p40405336205412"></a><a name="p40405336205412"></a>Delete federation protocol(s)</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p45105767205412"><a name="p45105767205412"></a><a name="p45105767205412"></a>openstack federation protocol delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p63600951205412"><a name="p63600951205412"></a><a name="p63600951205412"></a>-</p>
</td>
</tr>
<tr id="row5633389720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p6856131516312"><a name="p6856131516312"></a><a name="p6856131516312"></a>109</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p33714068205412"><a name="p33714068205412"></a><a name="p33714068205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p6071801205412"><a name="p6071801205412"></a><a name="p6071801205412"></a>List federation protocols</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p35523553205412"><a name="p35523553205412"></a><a name="p35523553205412"></a>openstack federation protocol list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p30443978205412"><a name="p30443978205412"></a><a name="p30443978205412"></a>-</p>
</td>
</tr>
<tr id="row5179500720253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p138563156319"><a name="p138563156319"></a><a name="p138563156319"></a>110</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p56569604205412"><a name="p56569604205412"></a><a name="p56569604205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p65471523205412"><a name="p65471523205412"></a><a name="p65471523205412"></a>Set federation protocol properties</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p28875524205412"><a name="p28875524205412"></a><a name="p28875524205412"></a>openstack federation protocol set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p38497318205412"><a name="p38497318205412"></a><a name="p38497318205412"></a>-</p>
</td>
</tr>
<tr id="row6416873620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1385681513316"><a name="p1385681513316"></a><a name="p1385681513316"></a>111</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p28905838205412"><a name="p28905838205412"></a><a name="p28905838205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p4400485205412"><a name="p4400485205412"></a><a name="p4400485205412"></a>Display federation protocol Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p27399519205412"><a name="p27399519205412"></a><a name="p27399519205412"></a>openstack federation protocol show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p41740762205412"><a name="p41740762205412"></a><a name="p41740762205412"></a>-</p>
</td>
</tr>
<tr id="row5005468620253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1885619151436"><a name="p1885619151436"></a><a name="p1885619151436"></a>112</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p20461151205412"><a name="p20461151205412"></a><a name="p20461151205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p2051408205412"><a name="p2051408205412"></a><a name="p2051408205412"></a>Create new identity provider</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p19391106205412"><a name="p19391106205412"></a><a name="p19391106205412"></a>openstack identity provider create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p44732023205412"><a name="p44732023205412"></a><a name="p44732023205412"></a>-</p>
</td>
</tr>
<tr id="row181104920253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p18856131517317"><a name="p18856131517317"></a><a name="p18856131517317"></a>113</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p8994665205412"><a name="p8994665205412"></a><a name="p8994665205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p64405875205412"><a name="p64405875205412"></a><a name="p64405875205412"></a>Delete identity provider(s)</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p9235454205412"><a name="p9235454205412"></a><a name="p9235454205412"></a>openstack identity provider delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p58189708205412"><a name="p58189708205412"></a><a name="p58189708205412"></a>-</p>
</td>
</tr>
<tr id="row5600030420253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p185681514312"><a name="p185681514312"></a><a name="p185681514312"></a>114</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p51351580205412"><a name="p51351580205412"></a><a name="p51351580205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p20187487205412"><a name="p20187487205412"></a><a name="p20187487205412"></a>List identity providers</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p39574883205412"><a name="p39574883205412"></a><a name="p39574883205412"></a>openstack identity provider list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p13157546205412"><a name="p13157546205412"></a><a name="p13157546205412"></a>-</p>
</td>
</tr>
<tr id="row257373220253"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p128569151934"><a name="p128569151934"></a><a name="p128569151934"></a>115</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p60788231205412"><a name="p60788231205412"></a><a name="p60788231205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p29044387205412"><a name="p29044387205412"></a><a name="p29044387205412"></a>Set identity provider properties</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p21062720205412"><a name="p21062720205412"></a><a name="p21062720205412"></a>openstack identity provider set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p53180256205412"><a name="p53180256205412"></a><a name="p53180256205412"></a>-</p>
</td>
</tr>
<tr id="row58294913204833"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p585651515310"><a name="p585651515310"></a><a name="p585651515310"></a>116</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p12640443205412"><a name="p12640443205412"></a><a name="p12640443205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p8125647205412"><a name="p8125647205412"></a><a name="p8125647205412"></a>Show identity provider Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p57569318205412"><a name="p57569318205412"></a><a name="p57569318205412"></a>openstack identity provider show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p13308734205412"><a name="p13308734205412"></a><a name="p13308734205412"></a>-</p>
</td>
</tr>
<tr id="row46955919204853"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p14856715232"><a name="p14856715232"></a><a name="p14856715232"></a>117</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p58241479205412"><a name="p58241479205412"></a><a name="p58241479205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p7094644205412"><a name="p7094644205412"></a><a name="p7094644205412"></a>Create new mapping</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p8549028205412"><a name="p8549028205412"></a><a name="p8549028205412"></a>openstack mapping create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p48868822205412"><a name="p48868822205412"></a><a name="p48868822205412"></a>-</p>
</td>
</tr>
<tr id="row382112320496"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p785611512317"><a name="p785611512317"></a><a name="p785611512317"></a>118</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p26995900205412"><a name="p26995900205412"></a><a name="p26995900205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p4852770205412"><a name="p4852770205412"></a><a name="p4852770205412"></a>Delete mapping(s)</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p50175819205412"><a name="p50175819205412"></a><a name="p50175819205412"></a>openstack mapping delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p14851765205412"><a name="p14851765205412"></a><a name="p14851765205412"></a>-</p>
</td>
</tr>
<tr id="row4624601620496"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p58566151135"><a name="p58566151135"></a><a name="p58566151135"></a>119</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p11108137205412"><a name="p11108137205412"></a><a name="p11108137205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p17165928205412"><a name="p17165928205412"></a><a name="p17165928205412"></a>List mappings</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p37432234205412"><a name="p37432234205412"></a><a name="p37432234205412"></a>openstack mapping list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p28622701205412"><a name="p28622701205412"></a><a name="p28622701205412"></a>-</p>
</td>
</tr>
<tr id="row61060759204917"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p48561515034"><a name="p48561515034"></a><a name="p48561515034"></a>120</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p36477086205412"><a name="p36477086205412"></a><a name="p36477086205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p62208983205412"><a name="p62208983205412"></a><a name="p62208983205412"></a>Set mapping properties</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p32739153205412"><a name="p32739153205412"></a><a name="p32739153205412"></a>openstack mapping set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p18131854205412"><a name="p18131854205412"></a><a name="p18131854205412"></a>-</p>
</td>
</tr>
<tr id="row33894889204917"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p18561915431"><a name="p18561915431"></a><a name="p18561915431"></a>121</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p44493485205412"><a name="p44493485205412"></a><a name="p44493485205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p805374205412"><a name="p805374205412"></a><a name="p805374205412"></a>Show mapping Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p4637650205412"><a name="p4637650205412"></a><a name="p4637650205412"></a>openstack mapping show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p17236135205412"><a name="p17236135205412"></a><a name="p17236135205412"></a>-</p>
</td>
</tr>
<tr id="row41636695204917"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1185616151732"><a name="p1185616151732"></a><a name="p1185616151732"></a>122</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p190691205412"><a name="p190691205412"></a><a name="p190691205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p6336622205412"><a name="p6336622205412"></a><a name="p6336622205412"></a>List module versions</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p55477434205412"><a name="p55477434205412"></a><a name="p55477434205412"></a>openstack module list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p16948809205412"><a name="p16948809205412"></a><a name="p16948809205412"></a>-</p>
</td>
</tr>
<tr id="row34314162204917"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1985661510318"><a name="p1985661510318"></a><a name="p1985661510318"></a>123</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p9308370205412"><a name="p9308370205412"></a><a name="p9308370205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p3377334205412"><a name="p3377334205412"></a><a name="p3377334205412"></a>List projects</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p54038427205412"><a name="p54038427205412"></a><a name="p54038427205412"></a>openstack project list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1561475713306"><a name="p1561475713306"></a><a name="p1561475713306"></a>-</p>
</td>
</tr>
<tr id="row31926666204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p685617157311"><a name="p685617157311"></a><a name="p685617157311"></a>124</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p58393098205412"><a name="p58393098205412"></a><a name="p58393098205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p37989990205412"><a name="p37989990205412"></a><a name="p37989990205412"></a>Show project Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p32039941205412"><a name="p32039941205412"></a><a name="p32039941205412"></a>openstack project show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p13835175743019"><a name="p13835175743019"></a><a name="p13835175743019"></a>-</p>
</td>
</tr>
<tr id="row63463259204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1185681515314"><a name="p1185681515314"></a><a name="p1185681515314"></a>125</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p65801754205412"><a name="p65801754205412"></a><a name="p65801754205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p52952848205412"><a name="p52952848205412"></a><a name="p52952848205412"></a>List services</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p19137415205412"><a name="p19137415205412"></a><a name="p19137415205412"></a>openstack service list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1549155816300"><a name="p1549155816300"></a><a name="p1549155816300"></a>-</p>
</td>
</tr>
<tr id="row49267880204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p385671513318"><a name="p385671513318"></a><a name="p385671513318"></a>126</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p59058323205412"><a name="p59058323205412"></a><a name="p59058323205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p24222273205412"><a name="p24222273205412"></a><a name="p24222273205412"></a>Show service Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p4272562205412"><a name="p4272562205412"></a><a name="p4272562205412"></a>openstack service show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p11268358143016"><a name="p11268358143016"></a><a name="p11268358143016"></a>-</p>
</td>
</tr>
<tr id="row55636546204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p6856115839"><a name="p6856115839"></a><a name="p6856115839"></a>127</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p25579268205412"><a name="p25579268205412"></a><a name="p25579268205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p5644683205412"><a name="p5644683205412"></a><a name="p5644683205412"></a>Issue new token</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p40154133205412"><a name="p40154133205412"></a><a name="p40154133205412"></a>openstack token issue</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p4608165813307"><a name="p4608165813307"></a><a name="p4608165813307"></a>-</p>
</td>
</tr>
<tr id="row5497592204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1885617151734"><a name="p1885617151734"></a><a name="p1885617151734"></a>128</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p57524478205412"><a name="p57524478205412"></a><a name="p57524478205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p31586430205412"><a name="p31586430205412"></a><a name="p31586430205412"></a>Create new user</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p37884481205412"><a name="p37884481205412"></a><a name="p37884481205412"></a>openstack user create</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p28171758163020"><a name="p28171758163020"></a><a name="p28171758163020"></a>-</p>
</td>
</tr>
<tr id="row64893851204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p10856615433"><a name="p10856615433"></a><a name="p10856615433"></a>129</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p2244624205412"><a name="p2244624205412"></a><a name="p2244624205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p28476585205412"><a name="p28476585205412"></a><a name="p28476585205412"></a>Delete user(s)</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p6706629205412"><a name="p6706629205412"></a><a name="p6706629205412"></a>openstack user delete</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p1332115918303"><a name="p1332115918303"></a><a name="p1332115918303"></a>-</p>
</td>
</tr>
<tr id="row44327674204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p285613159315"><a name="p285613159315"></a><a name="p285613159315"></a>130</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p44388298205412"><a name="p44388298205412"></a><a name="p44388298205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p20475293205412"><a name="p20475293205412"></a><a name="p20475293205412"></a>List users</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p17451569205412"><a name="p17451569205412"></a><a name="p17451569205412"></a>openstack user list</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p72571659133011"><a name="p72571659133011"></a><a name="p72571659133011"></a>-</p>
</td>
</tr>
<tr id="row46338534204929"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1856515835"><a name="p1856515835"></a><a name="p1856515835"></a>131</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p21853629205412"><a name="p21853629205412"></a><a name="p21853629205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p42065129205412"><a name="p42065129205412"></a><a name="p42065129205412"></a>Set user properties</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p40680726205412"><a name="p40680726205412"></a><a name="p40680726205412"></a>openstack user set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p9461446205412"><a name="p9461446205412"></a><a name="p9461446205412"></a>-</p>
</td>
</tr>
<tr id="row28760954205042"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p885617152034"><a name="p885617152034"></a><a name="p885617152034"></a>132</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p42498425205412"><a name="p42498425205412"></a><a name="p42498425205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p42778142205412"><a name="p42778142205412"></a><a name="p42778142205412"></a>Show user Details</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p11845124205412"><a name="p11845124205412"></a><a name="p11845124205412"></a>openstack user show</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p14438829205412"><a name="p14438829205412"></a><a name="p14438829205412"></a>-</p>
</td>
</tr>
<tr id="row30621807205042"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p1585661510313"><a name="p1585661510313"></a><a name="p1585661510313"></a>133</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p2466957205412"><a name="p2466957205412"></a><a name="p2466957205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p2162379205412"><a name="p2162379205412"></a><a name="p2162379205412"></a>Change current user password</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p6020746205412"><a name="p6020746205412"></a><a name="p6020746205412"></a>openstack user password set</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p47033420205412"><a name="p47033420205412"></a><a name="p47033420205412"></a>-</p>
</td>
</tr>
<tr id="row26550287205042"><td class="cellrowborder" valign="top" width="8.08080808080808%" headers="mcps1.1.6.1.1 "><p id="p19856171510313"><a name="p19856171510313"></a><a name="p19856171510313"></a>134</p>
</td>
<td class="cellrowborder" valign="top" width="19.19191919191919%" headers="mcps1.1.6.1.2 "><p id="p36176522205412"><a name="p36176522205412"></a><a name="p36176522205412"></a>Keystone</p>
</td>
<td class="cellrowborder" valign="top" width="22.222222222222225%" headers="mcps1.1.6.1.3 "><p id="p3329664205412"><a name="p3329664205412"></a><a name="p3329664205412"></a>Display help</p>
</td>
<td class="cellrowborder" valign="top" width="33.33333333333333%" headers="mcps1.1.6.1.4 "><p id="p2126393205412"><a name="p2126393205412"></a><a name="p2126393205412"></a>openstack help</p>
</td>
<td class="cellrowborder" valign="top" width="17.17171717171717%" headers="mcps1.1.6.1.5 "><p id="p33941043205412"><a name="p33941043205412"></a><a name="p33941043205412"></a>-</p>
</td>
</tr>
</tbody>
</table>

## Extended CLI<a name="section18644171710520"></a>

<a name="table0261940165516"></a>
<table><thead align="left"><tr id="row1626214095518"><th class="cellrowborder" valign="top" width="8.290000000000001%" id="mcps1.1.6.1.1"><p id="p143111154182012"><a name="p143111154182012"></a><a name="p143111154182012"></a>序号</p>
</th>
<th class="cellrowborder" valign="top" width="17.32%" id="mcps1.1.6.1.2"><p id="p3468185462019"><a name="p3468185462019"></a><a name="p3468185462019"></a>组件</p>
</th>
<th class="cellrowborder" valign="top" width="21.4%" id="mcps1.1.6.1.3"><p id="p1661465414208"><a name="p1661465414208"></a><a name="p1661465414208"></a>功能</p>
</th>
<th class="cellrowborder" valign="top" width="19.36%" id="mcps1.1.6.1.4"><p id="p127781154162016"><a name="p127781154162016"></a><a name="p127781154162016"></a>命令行</p>
</th>
<th class="cellrowborder" valign="top" width="33.629999999999995%" id="mcps1.1.6.1.5"><p id="p192835442016"><a name="p192835442016"></a><a name="p192835442016"></a>备注</p>
</th>
</tr>
</thead>
<tbody><tr id="row1229794018550"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p2029874016554"><a name="p2029874016554"></a><a name="p2029874016554"></a>1</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p9298194013558"><a name="p9298194013558"></a><a name="p9298194013558"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p14298540115517"><a name="p14298540115517"></a><a name="p14298540115517"></a>Add Metric Data</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1929817403552"><a name="p1929817403552"></a><a name="p1929817403552"></a>openstack metric data create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p529914013552"><a name="p529914013552"></a><a name="p529914013552"></a>-</p>
</td>
</tr>
<tr id="row1729994018554"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p152997409555"><a name="p152997409555"></a><a name="p152997409555"></a>2</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p16299154013552"><a name="p16299154013552"></a><a name="p16299154013552"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p113001440195515"><a name="p113001440195515"></a><a name="p113001440195515"></a>List Metrics</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1130084055518"><a name="p1130084055518"></a><a name="p1130084055518"></a>openstack metric list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p3300184085518"><a name="p3300184085518"></a><a name="p3300184085518"></a>-</p>
</td>
</tr>
<tr id="row830174035510"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p5301124085518"><a name="p5301124085518"></a><a name="p5301124085518"></a>3</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1030184010553"><a name="p1030184010553"></a><a name="p1030184010553"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p23011840205513"><a name="p23011840205513"></a><a name="p23011840205513"></a>List Metric Data</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1830119408557"><a name="p1830119408557"></a><a name="p1830119408557"></a>openstack metric data list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p16302144075511"><a name="p16302144075511"></a><a name="p16302144075511"></a>-</p>
</td>
</tr>
<tr id="row14302124011552"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p13303640125515"><a name="p13303640125515"></a><a name="p13303640125515"></a>4</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1930313403552"><a name="p1930313403552"></a><a name="p1930313403552"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p33033408550"><a name="p33033408550"></a><a name="p33033408550"></a>List Favorite Metrics</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p330394075511"><a name="p330394075511"></a><a name="p330394075511"></a>openstack metric favorite list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1430334016558"><a name="p1430334016558"></a><a name="p1430334016558"></a></p>
<p id="p19303840195517"><a name="p19303840195517"></a><a name="p19303840195517"></a>Only the data of the old console can be queried through the API.</p>
</td>
</tr>
<tr id="row33041140135520"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p030414014554"><a name="p030414014554"></a><a name="p030414014554"></a>5</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p123041740135516"><a name="p123041740135516"></a><a name="p123041740135516"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p13304124065510"><a name="p13304124065510"></a><a name="p13304124065510"></a>List Alarms</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p730516408554"><a name="p730516408554"></a><a name="p730516408554"></a>openstack alarm list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p8138111910315"><a name="p8138111910315"></a><a name="p8138111910315"></a>-</p>
</td>
</tr>
<tr id="row130564010556"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p123068403550"><a name="p123068403550"></a><a name="p123068403550"></a>6</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p530664025519"><a name="p530664025519"></a><a name="p530664025519"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p330612400551"><a name="p330612400551"></a><a name="p330612400551"></a>Show Alarm</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p930634015559"><a name="p930634015559"></a><a name="p930634015559"></a>openstack alarm show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p836251919314"><a name="p836251919314"></a><a name="p836251919314"></a>-</p>
</td>
</tr>
<tr id="row63077407558"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p123071440165516"><a name="p123071440165516"></a><a name="p123071440165516"></a>7</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p23072408557"><a name="p23072408557"></a><a name="p23072408557"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p15307440145518"><a name="p15307440145518"></a><a name="p15307440145518"></a>Enable Alarm</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p7307204015519"><a name="p7307204015519"></a><a name="p7307204015519"></a>openstack alarm enable</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p185721819183117"><a name="p185721819183117"></a><a name="p185721819183117"></a>-</p>
</td>
</tr>
<tr id="row2030784095510"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1930794014554"><a name="p1930794014554"></a><a name="p1930794014554"></a>8</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p43081640115517"><a name="p43081640115517"></a><a name="p43081640115517"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p163081240165513"><a name="p163081240165513"></a><a name="p163081240165513"></a>Disable Alarm</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p23081040115518"><a name="p23081040115518"></a><a name="p23081040115518"></a>openstack alarm disable</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1278821913316"><a name="p1278821913316"></a><a name="p1278821913316"></a>-</p>
</td>
</tr>
<tr id="row9308340155514"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p11308124016559"><a name="p11308124016559"></a><a name="p11308124016559"></a>9</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p030874018555"><a name="p030874018555"></a><a name="p030874018555"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p10308740135515"><a name="p10308740135515"></a><a name="p10308740135515"></a>Delete Alarm</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p3309134085514"><a name="p3309134085514"></a><a name="p3309134085514"></a>openstack alarm delete</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1699591912316"><a name="p1699591912316"></a><a name="p1699591912316"></a>-</p>
</td>
</tr>
<tr id="row20309104015550"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p43092406556"><a name="p43092406556"></a><a name="p43092406556"></a>10</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p930984018559"><a name="p930984018559"></a><a name="p930984018559"></a>Cloud Eye</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1030954085518"><a name="p1030954085518"></a><a name="p1030954085518"></a>List Quotas</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p2030914013552"><a name="p2030914013552"></a><a name="p2030914013552"></a>openstack quota list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p102071820183115"><a name="p102071820183115"></a><a name="p102071820183115"></a>-</p>
</td>
</tr>
<tr id="row531064013555"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p20311194018558"><a name="p20311194018558"></a><a name="p20311194018558"></a>11</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p831112404551"><a name="p831112404551"></a><a name="p831112404551"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p153171840135520"><a name="p153171840135520"></a><a name="p153171840135520"></a>Querying AS Configurations</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p83178407552"><a name="p83178407552"></a><a name="p83178407552"></a>openstack as config list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p184111520133120"><a name="p184111520133120"></a><a name="p184111520133120"></a>-</p>
</td>
</tr>
<tr id="row5317164016559"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p12317184015554"><a name="p12317184015554"></a><a name="p12317184015554"></a>12</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p11317134045517"><a name="p11317134045517"></a><a name="p11317134045517"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1231714013557"><a name="p1231714013557"></a><a name="p1231714013557"></a>Creating an AS Configuration</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p18318204019552"><a name="p18318204019552"></a><a name="p18318204019552"></a>openstack as config create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p761962003113"><a name="p761962003113"></a><a name="p761962003113"></a>-</p>
</td>
</tr>
<tr id="row7318240185519"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p11318144014559"><a name="p11318144014559"></a><a name="p11318144014559"></a>13</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1631810407553"><a name="p1631810407553"></a><a name="p1631810407553"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p031816404555"><a name="p031816404555"></a><a name="p031816404555"></a>Querying AS Configuration Details</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p13318154045520"><a name="p13318154045520"></a><a name="p13318154045520"></a>openstack as config show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p75939249315"><a name="p75939249315"></a><a name="p75939249315"></a>-</p>
</td>
</tr>
<tr id="row53189405557"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p10318640145510"><a name="p10318640145510"></a><a name="p10318640145510"></a>14</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p631854019550"><a name="p631854019550"></a><a name="p631854019550"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p13199401559"><a name="p13199401559"></a><a name="p13199401559"></a>Deleting an AS Configuration</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p183191402555"><a name="p183191402555"></a><a name="p183191402555"></a>openstack as config delete</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p13814224133120"><a name="p13814224133120"></a><a name="p13814224133120"></a>-</p>
</td>
</tr>
<tr id="row1319174014552"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p7319440125520"><a name="p7319440125520"></a><a name="p7319440125520"></a>15</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1231924085510"><a name="p1231924085510"></a><a name="p1231924085510"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p33191240185515"><a name="p33191240185515"></a><a name="p33191240185515"></a>Creating an AS Group</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p932074014559"><a name="p932074014559"></a><a name="p932074014559"></a>openstack as group create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p3281425133120"><a name="p3281425133120"></a><a name="p3281425133120"></a>-</p>
</td>
</tr>
<tr id="row1232014405556"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p83201940175516"><a name="p83201940175516"></a><a name="p83201940175516"></a>16</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p16320140115510"><a name="p16320140115510"></a><a name="p16320140115510"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p15320114018552"><a name="p15320114018552"></a><a name="p15320114018552"></a>Modifying an AS Group</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p3320940135510"><a name="p3320940135510"></a><a name="p3320940135510"></a>openstack as group edit</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1224912257310"><a name="p1224912257310"></a><a name="p1224912257310"></a>-</p>
</td>
</tr>
<tr id="row16321104045510"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p132184019552"><a name="p132184019552"></a><a name="p132184019552"></a>17</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p13321104019554"><a name="p13321104019554"></a><a name="p13321104019554"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p43211040105512"><a name="p43211040105512"></a><a name="p43211040105512"></a>Querying AS Groups</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p43211940105517"><a name="p43211940105517"></a><a name="p43211940105517"></a>openstack as group list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1946712503118"><a name="p1946712503118"></a><a name="p1946712503118"></a>-</p>
</td>
</tr>
<tr id="row6323104095519"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p103231407554"><a name="p103231407554"></a><a name="p103231407554"></a>18</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p33231140135517"><a name="p33231140135517"></a><a name="p33231140135517"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1132364015558"><a name="p1132364015558"></a><a name="p1132364015558"></a>Querying AS Group Details</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1532334014559"><a name="p1532334014559"></a><a name="p1532334014559"></a>openstack as group show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p12684182510312"><a name="p12684182510312"></a><a name="p12684182510312"></a>-</p>
</td>
</tr>
<tr id="row832415400557"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p8324184045511"><a name="p8324184045511"></a><a name="p8324184045511"></a>19</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p9324540115512"><a name="p9324540115512"></a><a name="p9324540115512"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p133251406558"><a name="p133251406558"></a><a name="p133251406558"></a>Enabling an AS Group</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p232514407551"><a name="p232514407551"></a><a name="p232514407551"></a>openstack as group resume</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p2897825113116"><a name="p2897825113116"></a><a name="p2897825113116"></a>-</p>
</td>
</tr>
<tr id="row93251740145512"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p53251940175510"><a name="p53251940175510"></a><a name="p53251940175510"></a>20</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p11326440105512"><a name="p11326440105512"></a><a name="p11326440105512"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p0326440165510"><a name="p0326440165510"></a><a name="p0326440165510"></a>Disabling an AS Group</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p133269407558"><a name="p133269407558"></a><a name="p133269407558"></a>openstack as group pause</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p7111192615315"><a name="p7111192615315"></a><a name="p7111192615315"></a>-</p>
</td>
</tr>
<tr id="row732794025516"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p10327840165514"><a name="p10327840165514"></a><a name="p10327840165514"></a>21</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1332834019559"><a name="p1332834019559"></a><a name="p1332834019559"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p63286402558"><a name="p63286402558"></a><a name="p63286402558"></a>Deleting an AS Group</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p2032815404559"><a name="p2032815404559"></a><a name="p2032815404559"></a>openstack as group delete</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p4513183133118"><a name="p4513183133118"></a><a name="p4513183133118"></a>-</p>
</td>
</tr>
<tr id="row1032910407551"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p163301402554"><a name="p163301402554"></a><a name="p163301402554"></a>22</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p7330040105514"><a name="p7330040105514"></a><a name="p7330040105514"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p433054014554"><a name="p433054014554"></a><a name="p433054014554"></a>Querying Instances in an AS Group</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p103309408553"><a name="p103309408553"></a><a name="p103309408553"></a>openstack as instance list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p223416321314"><a name="p223416321314"></a><a name="p223416321314"></a>-</p>
</td>
</tr>
<tr id="row3331134005515"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p733124019556"><a name="p733124019556"></a><a name="p733124019556"></a>23</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p533194025512"><a name="p533194025512"></a><a name="p533194025512"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p3332134015553"><a name="p3332134015553"></a><a name="p3332134015553"></a>Removing Instances from an AS Group</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p633214017552"><a name="p633214017552"></a><a name="p633214017552"></a>openstack as instance remove</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p7434103216313"><a name="p7434103216313"></a><a name="p7434103216313"></a>-</p>
</td>
</tr>
<tr id="row4332340155517"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p153331140105519"><a name="p153331140105519"></a><a name="p153331140105519"></a>24</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p103338403551"><a name="p103338403551"></a><a name="p103338403551"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1933320409551"><a name="p1933320409551"></a><a name="p1933320409551"></a>Batch Adding Instances</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p10333840185514"><a name="p10333840185514"></a><a name="p10333840185514"></a>openstack as instance add</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p7635132143110"><a name="p7635132143110"></a><a name="p7635132143110"></a>-</p>
</td>
</tr>
<tr id="row83343401556"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p2334134011553"><a name="p2334134011553"></a><a name="p2334134011553"></a>25</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p20334134014552"><a name="p20334134014552"></a><a name="p20334134014552"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p11334124019551"><a name="p11334124019551"></a><a name="p11334124019551"></a>Creating an AS Policy</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1233584085514"><a name="p1233584085514"></a><a name="p1233584085514"></a>openstack as policy create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p28383327317"><a name="p28383327317"></a><a name="p28383327317"></a>-</p>
</td>
</tr>
<tr id="row633504018551"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p17335134065518"><a name="p17335134065518"></a><a name="p17335134065518"></a>26</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p5337240115512"><a name="p5337240115512"></a><a name="p5337240115512"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p2337144085511"><a name="p2337144085511"></a><a name="p2337144085511"></a>Modifying an AS Policy</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p18337184065512"><a name="p18337184065512"></a><a name="p18337184065512"></a>openstack as policy edit</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p94717332314"><a name="p94717332314"></a><a name="p94717332314"></a>-</p>
</td>
</tr>
<tr id="row17337164016550"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p633704020556"><a name="p633704020556"></a><a name="p633704020556"></a>27</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p43373404551"><a name="p43373404551"></a><a name="p43373404551"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p533724095519"><a name="p533724095519"></a><a name="p533724095519"></a>Querying AS Policies</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p18337540205511"><a name="p18337540205511"></a><a name="p18337540205511"></a>openstack as policy list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p725063318318"><a name="p725063318318"></a><a name="p725063318318"></a>-</p>
</td>
</tr>
<tr id="row18340740125518"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p734034019555"><a name="p734034019555"></a><a name="p734034019555"></a>28</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1834017403553"><a name="p1834017403553"></a><a name="p1834017403553"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p12340144035511"><a name="p12340144035511"></a><a name="p12340144035511"></a>Disabling an AS Policy</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p11340144035515"><a name="p11340144035515"></a><a name="p11340144035515"></a>openstack as policy pause</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p10455433173119"><a name="p10455433173119"></a><a name="p10455433173119"></a>-</p>
</td>
</tr>
<tr id="row1334019407553"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p16341114018550"><a name="p16341114018550"></a><a name="p16341114018550"></a>29</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1834174019554"><a name="p1834174019554"></a><a name="p1834174019554"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p234119409555"><a name="p234119409555"></a><a name="p234119409555"></a>Querying AS Policy Details</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p734117408559"><a name="p734117408559"></a><a name="p734117408559"></a>openstack as policy show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p81611739163114"><a name="p81611739163114"></a><a name="p81611739163114"></a>-</p>
</td>
</tr>
<tr id="row11342164025520"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1034364010552"><a name="p1034364010552"></a><a name="p1034364010552"></a>30</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p234344017553"><a name="p234344017553"></a><a name="p234344017553"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p15343104055516"><a name="p15343104055516"></a><a name="p15343104055516"></a>Enabling an AS Policy</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p4343174012553"><a name="p4343174012553"></a><a name="p4343174012553"></a>openstack as policy resume</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p15377183973114"><a name="p15377183973114"></a><a name="p15377183973114"></a>-</p>
</td>
</tr>
<tr id="row2343194015518"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1334311409559"><a name="p1334311409559"></a><a name="p1334311409559"></a>31</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p43433403558"><a name="p43433403558"></a><a name="p43433403558"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1534344011559"><a name="p1534344011559"></a><a name="p1534344011559"></a>Executing an AS Policy</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p534344013557"><a name="p534344013557"></a><a name="p534344013557"></a>openstack as policy execute</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p17597183913116"><a name="p17597183913116"></a><a name="p17597183913116"></a>-</p>
</td>
</tr>
<tr id="row1345114075517"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p163455407556"><a name="p163455407556"></a><a name="p163455407556"></a>32</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p8345140175517"><a name="p8345140175517"></a><a name="p8345140175517"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p193456408555"><a name="p193456408555"></a><a name="p193456408555"></a>Deleting an AS Policy</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p23451340105514"><a name="p23451340105514"></a><a name="p23451340105514"></a>openstack as policy delete</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p381393911313"><a name="p381393911313"></a><a name="p381393911313"></a>-</p>
</td>
</tr>
<tr id="row1734634020552"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p334674010555"><a name="p334674010555"></a><a name="p334674010555"></a>33</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p13346164020556"><a name="p13346164020556"></a><a name="p13346164020556"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p53469404559"><a name="p53469404559"></a><a name="p53469404559"></a>Querying Scaling Action Logs</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1034644014554"><a name="p1034644014554"></a><a name="p1034644014554"></a>openstack as log list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p321540153113"><a name="p321540153113"></a><a name="p321540153113"></a>-</p>
</td>
</tr>
<tr id="row1734612408552"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p7346104005511"><a name="p7346104005511"></a><a name="p7346104005511"></a>34</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p7348540105518"><a name="p7348540105518"></a><a name="p7348540105518"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p334864016550"><a name="p334864016550"></a><a name="p334864016550"></a>Querying Quotas for AS Groups and AS Configurations</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p834814055511"><a name="p834814055511"></a><a name="p834814055511"></a>openstack as quota list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p14226940103112"><a name="p14226940103112"></a><a name="p14226940103112"></a>-</p>
</td>
</tr>
<tr id="row23481740185517"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p16348114017557"><a name="p16348114017557"></a><a name="p16348114017557"></a>35</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p11348154011552"><a name="p11348154011552"></a><a name="p11348154011552"></a>Auto Scaling</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p183484406556"><a name="p183484406556"></a><a name="p183484406556"></a>Querying Quotas for AS Instances and AS Policies</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p8349164055510"><a name="p8349164055510"></a><a name="p8349164055510"></a>openstack as quota list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p12433134010313"><a name="p12433134010313"></a><a name="p12433134010313"></a>-</p>
</td>
</tr>
<tr id="row434918405557"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p183491840185519"><a name="p183491840185519"></a><a name="p183491840185519"></a>36</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p734914011559"><a name="p734914011559"></a><a name="p734914011559"></a>Volume Backup Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p18349154095516"><a name="p18349154095516"></a><a name="p18349154095516"></a>Create Volume Backup</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1234910406556"><a name="p1234910406556"></a><a name="p1234910406556"></a>openstack volume backup ext create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p15651144018315"><a name="p15651144018315"></a><a name="p15651144018315"></a>-</p>
</td>
</tr>
<tr id="row9349144015554"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p153498402557"><a name="p153498402557"></a><a name="p153498402557"></a>37</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p23491540175511"><a name="p23491540175511"></a><a name="p23491540175511"></a>Volume Backup Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p15349540195514"><a name="p15349540195514"></a><a name="p15349540195514"></a>Restore Volume Backup</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p3349114016558"><a name="p3349114016558"></a><a name="p3349114016558"></a>openstack volume backup ext restore</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1176117443317"><a name="p1176117443317"></a><a name="p1176117443317"></a>-</p>
</td>
</tr>
<tr id="row93509402552"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p4350340135519"><a name="p4350340135519"></a><a name="p4350340135519"></a>38</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1735014005511"><a name="p1735014005511"></a><a name="p1735014005511"></a>Volume Backup Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p19350184014559"><a name="p19350184014559"></a><a name="p19350184014559"></a>Show Volume Backup Job</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p3350124020556"><a name="p3350124020556"></a><a name="p3350124020556"></a>openstack volume backup job show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1296814443311"><a name="p1296814443311"></a><a name="p1296814443311"></a>-</p>
</td>
</tr>
<tr id="row8350144012555"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p83516408556"><a name="p83516408556"></a><a name="p83516408556"></a>39</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p735110405557"><a name="p735110405557"></a><a name="p735110405557"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p83511404551"><a name="p83511404551"></a><a name="p83511404551"></a>Creating a Key</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p12351134065517"><a name="p12351134065517"></a><a name="p12351134065517"></a>openstack kms key create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p17183184517311"><a name="p17183184517311"></a><a name="p17183184517311"></a>-</p>
</td>
</tr>
<tr id="row10351184010552"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p5351184018550"><a name="p5351184018550"></a><a name="p5351184018550"></a>40</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p11351184017558"><a name="p11351184017558"></a><a name="p11351184017558"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p335194012555"><a name="p335194012555"></a><a name="p335194012555"></a>Enabling a Key</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p14352340105510"><a name="p14352340105510"></a><a name="p14352340105510"></a>openstack kms key enable</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p340617456316"><a name="p340617456316"></a><a name="p340617456316"></a>-</p>
</td>
</tr>
<tr id="row153521940125514"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p183521140195510"><a name="p183521140195510"></a><a name="p183521140195510"></a>41</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p8352940125510"><a name="p8352940125510"></a><a name="p8352940125510"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p4352104011551"><a name="p4352104011551"></a><a name="p4352104011551"></a>Disabling a Key</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p193521240105510"><a name="p193521240105510"></a><a name="p193521240105510"></a>openstack kms key disable</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1622184517313"><a name="p1622184517313"></a><a name="p1622184517313"></a>-</p>
</td>
</tr>
<tr id="row11353164005510"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1835311409559"><a name="p1835311409559"></a><a name="p1835311409559"></a>42</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p335394075516"><a name="p335394075516"></a><a name="p335394075516"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1235320404552"><a name="p1235320404552"></a><a name="p1235320404552"></a>Scheduling the Deletion of a Key</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p035394011559"><a name="p035394011559"></a><a name="p035394011559"></a>openstack kms key schedule deletion</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p7824745173113"><a name="p7824745173113"></a><a name="p7824745173113"></a>-</p>
</td>
</tr>
<tr id="row7353194045520"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p235418405559"><a name="p235418405559"></a><a name="p235418405559"></a>43</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p153584409551"><a name="p153584409551"></a><a name="p153584409551"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p123591940125511"><a name="p123591940125511"></a><a name="p123591940125511"></a>Canceling the Scheduled Deletion of a Key</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p19359740165519"><a name="p19359740165519"></a><a name="p19359740165519"></a>openstack kms key cancel deletion</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p033144633116"><a name="p033144633116"></a><a name="p033144633116"></a>-</p>
</td>
</tr>
<tr id="row11359134019557"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p173591840155518"><a name="p173591840155518"></a><a name="p173591840155518"></a>44</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p15359164055518"><a name="p15359164055518"></a><a name="p15359164055518"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p6359140115510"><a name="p6359140115510"></a><a name="p6359140115510"></a>Querying the List of Keys</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p63593404553"><a name="p63593404553"></a><a name="p63593404553"></a>openstack kms key list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p4255144693111"><a name="p4255144693111"></a><a name="p4255144693111"></a>-</p>
</td>
</tr>
<tr id="row23604404556"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p436064019556"><a name="p436064019556"></a><a name="p436064019556"></a>45</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p23601240195514"><a name="p23601240195514"></a><a name="p23601240195514"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p8360114065517"><a name="p8360114065517"></a><a name="p8360114065517"></a>Querying the Information About a Key</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p11360340135514"><a name="p11360340135514"></a><a name="p11360340135514"></a>openstack kms key show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p974245016310"><a name="p974245016310"></a><a name="p974245016310"></a>-</p>
</td>
</tr>
<tr id="row53607400557"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p63601240115511"><a name="p63601240115511"></a><a name="p63601240115511"></a>46</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p183607402553"><a name="p183607402553"></a><a name="p183607402553"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p636014012554"><a name="p636014012554"></a><a name="p636014012554"></a>Creating Random Data</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p236014409551"><a name="p236014409551"></a><a name="p236014409551"></a>openstack kms random generate</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1595335013117"><a name="p1595335013117"></a><a name="p1595335013117"></a>-</p>
</td>
</tr>
<tr id="row73621140145513"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p3362194019559"><a name="p3362194019559"></a><a name="p3362194019559"></a>47</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p20362114017555"><a name="p20362114017555"></a><a name="p20362114017555"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p10362240125516"><a name="p10362240125516"></a><a name="p10362240125516"></a>Creating a Data Encryption Key</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p13621040175520"><a name="p13621040175520"></a><a name="p13621040175520"></a>openstack kms datakey create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p0173125113110"><a name="p0173125113110"></a><a name="p0173125113110"></a>-</p>
</td>
</tr>
<tr id="row63623401552"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p036212403559"><a name="p036212403559"></a><a name="p036212403559"></a>48</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p18362114016552"><a name="p18362114016552"></a><a name="p18362114016552"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p163629404553"><a name="p163629404553"></a><a name="p163629404553"></a>Creating a Plaintext-Free DEK</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p10362164095512"><a name="p10362164095512"></a><a name="p10362164095512"></a>openstack kms datakey create --without-plain-text</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1438975114314"><a name="p1438975114314"></a><a name="p1438975114314"></a>-</p>
</td>
</tr>
<tr id="row14362640105519"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p163639406553"><a name="p163639406553"></a><a name="p163639406553"></a>49</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1363124065515"><a name="p1363124065515"></a><a name="p1363124065515"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p33636400553"><a name="p33636400553"></a><a name="p33636400553"></a>Encrypting a DEK</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p93631140125514"><a name="p93631140125514"></a><a name="p93631140125514"></a>openstack kms datakey encrypt</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p8600651153120"><a name="p8600651153120"></a><a name="p8600651153120"></a>-</p>
</td>
</tr>
<tr id="row1236464085520"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1436412401552"><a name="p1436412401552"></a><a name="p1436412401552"></a>50</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p19364104015519"><a name="p19364104015519"></a><a name="p19364104015519"></a>Key Management Service</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p3364140125512"><a name="p3364140125512"></a><a name="p3364140125512"></a>Decrypting a DEK</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p636524055516"><a name="p636524055516"></a><a name="p636524055516"></a>openstack kms datakey decrypt</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p10823105111318"><a name="p10823105111318"></a><a name="p10823105111318"></a>-</p>
</td>
</tr>
<tr id="row7365104019558"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p73651240155510"><a name="p73651240155510"></a><a name="p73651240155510"></a>51</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p113653406555"><a name="p113653406555"></a><a name="p113653406555"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p63651402555"><a name="p63651402555"></a><a name="p63651402555"></a>Querying the Desktop List</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1936694035519"><a name="p1936694035519"></a><a name="p1936694035519"></a>openstack desktop list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p837552133111"><a name="p837552133111"></a><a name="p837552133111"></a>-</p>
</td>
</tr>
<tr id="row15366144016555"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p83661440175511"><a name="p83661440175511"></a><a name="p83661440175511"></a>52</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p133667404551"><a name="p133667404551"></a><a name="p133667404551"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p936604019551"><a name="p936604019551"></a><a name="p936604019551"></a>Querying the Desktop Details List</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1636614011550"><a name="p1636614011550"></a><a name="p1636614011550"></a>openstack desktop Details list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1625411521311"><a name="p1625411521311"></a><a name="p1625411521311"></a>-</p>
</td>
</tr>
<tr id="row10367124025515"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p636714401556"><a name="p636714401556"></a><a name="p636714401556"></a>53</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1736724035518"><a name="p1736724035518"></a><a name="p1736724035518"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p636711406557"><a name="p636711406557"></a><a name="p636711406557"></a>Creating Desktops</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p20367184014557"><a name="p20367184014557"></a><a name="p20367184014557"></a>openstack desktop create</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p62853576314"><a name="p62853576314"></a><a name="p62853576314"></a>-</p>
</td>
</tr>
<tr id="row7368154065510"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p193681140155516"><a name="p193681140155516"></a><a name="p193681140155516"></a>54</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p163681840195510"><a name="p163681840195510"></a><a name="p163681840195510"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p12368124016555"><a name="p12368124016555"></a><a name="p12368124016555"></a>Deleting Desktops</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p5368640195512"><a name="p5368640195512"></a><a name="p5368640195512"></a>openstack desktop delete</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p15492165710314"><a name="p15492165710314"></a><a name="p15492165710314"></a>-</p>
</td>
</tr>
<tr id="row43688408555"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p9369134045513"><a name="p9369134045513"></a><a name="p9369134045513"></a>55</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p036964085520"><a name="p036964085520"></a><a name="p036964085520"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1436917402557"><a name="p1436917402557"></a><a name="p1436917402557"></a>Restarting Desktops</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1336944018551"><a name="p1336944018551"></a><a name="p1336944018551"></a>openstack desktop reboot</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p15246558113110"><a name="p15246558113110"></a><a name="p15246558113110"></a>-</p>
</td>
</tr>
<tr id="row13369040175514"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1336924015553"><a name="p1336924015553"></a><a name="p1336924015553"></a>56</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1936964035519"><a name="p1936964035519"></a><a name="p1936964035519"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p437034035513"><a name="p437034035513"></a><a name="p437034035513"></a>Starting Desktops</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p16370154018556"><a name="p16370154018556"></a><a name="p16370154018556"></a>openstack desktop start</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p13452858193110"><a name="p13452858193110"></a><a name="p13452858193110"></a>-</p>
</td>
</tr>
<tr id="row1370840115512"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p6370140155520"><a name="p6370140155520"></a><a name="p6370140155520"></a>57</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p19370840155512"><a name="p19370840155512"></a><a name="p19370840155512"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p19370640125513"><a name="p19370640125513"></a><a name="p19370640125513"></a>Shutting Down Desktops</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p73701840195511"><a name="p73701840195511"></a><a name="p73701840195511"></a>openstack desktop stop</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1179715813118"><a name="p1179715813118"></a><a name="p1179715813118"></a>-</p>
</td>
</tr>
<tr id="row837112400550"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p4371154012555"><a name="p4371154012555"></a><a name="p4371154012555"></a>58</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p19371840135513"><a name="p19371840135513"></a><a name="p19371840135513"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p19371740155519"><a name="p19371740155519"></a><a name="p19371740155519"></a>Modifying Desktop Attributes</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p23711040185518"><a name="p23711040185518"></a><a name="p23711040185518"></a>openstack desktop edit</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1515115920311"><a name="p1515115920311"></a><a name="p1515115920311"></a>-</p>
</td>
</tr>
<tr id="row18372154010556"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p8372134018556"><a name="p8372134018556"></a><a name="p8372134018556"></a>59</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1537284015554"><a name="p1537284015554"></a><a name="p1537284015554"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p53721240155510"><a name="p53721240155510"></a><a name="p53721240155510"></a>Querying Desktop Details</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p93723409551"><a name="p93723409551"></a><a name="p93723409551"></a>openstack desktop show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p14233195915314"><a name="p14233195915314"></a><a name="p14233195915314"></a>-</p>
</td>
</tr>
<tr id="row937214406554"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1372840155517"><a name="p1372840155517"></a><a name="p1372840155517"></a>60</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1737313405552"><a name="p1737313405552"></a><a name="p1737313405552"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p193731140155515"><a name="p193731140155515"></a><a name="p193731140155515"></a>Querying the Desktop User List</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p437311406551"><a name="p437311406551"></a><a name="p437311406551"></a>openstack desktop user list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p18443185923116"><a name="p18443185923116"></a><a name="p18443185923116"></a>-</p>
</td>
</tr>
<tr id="row153731140185516"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1637374095513"><a name="p1637374095513"></a><a name="p1637374095513"></a>61</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p17373124013557"><a name="p17373124013557"></a><a name="p17373124013557"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p10373240135511"><a name="p10373240135511"></a><a name="p10373240135511"></a>Querying Desktop User Login Records</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p103735405550"><a name="p103735405550"></a><a name="p103735405550"></a>openstack desktop login list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p11271045325"><a name="p11271045325"></a><a name="p11271045325"></a>-</p>
</td>
</tr>
<tr id="row2374440185510"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p153754404553"><a name="p153754404553"></a><a name="p153754404553"></a>62</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p14375134017558"><a name="p14375134017558"></a><a name="p14375134017558"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p6375040155516"><a name="p6375040155516"></a><a name="p6375040155516"></a>Applying for Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p237519405556"><a name="p237519405556"></a><a name="p237519405556"></a>openstack workspace enable</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p723912413322"><a name="p723912413322"></a><a name="p723912413322"></a>-</p>
</td>
</tr>
<tr id="row1337684085517"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1377340125511"><a name="p1377340125511"></a><a name="p1377340125511"></a>63</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p7377114013557"><a name="p7377114013557"></a><a name="p7377114013557"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1377840115515"><a name="p1377840115515"></a><a name="p1377840115515"></a>Querying Workspace Details</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p7378144012555"><a name="p7378144012555"></a><a name="p7378144012555"></a>openstack workspace show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p2046617443214"><a name="p2046617443214"></a><a name="p2046617443214"></a>-</p>
</td>
</tr>
<tr id="row17379104065513"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p193791404554"><a name="p193791404554"></a><a name="p193791404554"></a>64</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1737915409557"><a name="p1737915409557"></a><a name="p1737915409557"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p8379194095519"><a name="p8379194095519"></a><a name="p8379194095519"></a>Modifying Workspace Attributes</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p43808400552"><a name="p43808400552"></a><a name="p43808400552"></a>openstack workspace edit</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1668724173216"><a name="p1668724173216"></a><a name="p1668724173216"></a>-</p>
</td>
</tr>
<tr id="row17380194011558"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p3380194019554"><a name="p3380194019554"></a><a name="p3380194019554"></a>65</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1638074015553"><a name="p1638074015553"></a><a name="p1638074015553"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p153806403553"><a name="p153806403553"></a><a name="p153806403553"></a>Canceling Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p123801140165516"><a name="p123801140165516"></a><a name="p123801140165516"></a>openstack workspace disable</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p129026483215"><a name="p129026483215"></a><a name="p129026483215"></a>-</p>
</td>
</tr>
<tr id="row10380640165513"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p133801403550"><a name="p133801403550"></a><a name="p133801403550"></a>66</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p16380104010554"><a name="p16380104010554"></a><a name="p16380104010554"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p938004016558"><a name="p938004016558"></a><a name="p938004016558"></a>Querying Policies</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p17380140205515"><a name="p17380140205515"></a><a name="p17380140205515"></a>openstack workspace policy show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p131249543215"><a name="p131249543215"></a><a name="p131249543215"></a>-</p>
</td>
</tr>
<tr id="row63807408554"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p17381164019557"><a name="p17381164019557"></a><a name="p17381164019557"></a>67</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1738154018550"><a name="p1738154018550"></a><a name="p1738154018550"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p20381194035516"><a name="p20381194035516"></a><a name="p20381194035516"></a>Modifying Policies</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p73811140135511"><a name="p73811140135511"></a><a name="p73811140135511"></a>openstack workspace policy edit</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p635012510323"><a name="p635012510323"></a><a name="p635012510323"></a>-</p>
</td>
</tr>
<tr id="row838114016559"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p0381174014552"><a name="p0381174014552"></a><a name="p0381174014552"></a>68</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p183810409557"><a name="p183810409557"></a><a name="p183810409557"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p18382540125518"><a name="p18382540125518"></a><a name="p18382540125518"></a>Querying the Product List</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p6382340145514"><a name="p6382340145514"></a><a name="p6382340145514"></a>openstack workspace product list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p155868514322"><a name="p155868514322"></a><a name="p155868514322"></a>-</p>
</td>
</tr>
<tr id="row23822040115514"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p19382104010557"><a name="p19382104010557"></a><a name="p19382104010557"></a>69</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p438234010558"><a name="p438234010558"></a><a name="p438234010558"></a>Workspace</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p19382184075514"><a name="p19382184075514"></a><a name="p19382184075514"></a>Asynchronous Job Query</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1238244045514"><a name="p1238244045514"></a><a name="p1238244045514"></a>openstack workspace job show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p19384154055518"><a name="p19384154055518"></a><a name="p19384154055518"></a>-</p>
</td>
</tr>
<tr id="row153841340185513"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p538484025513"><a name="p538484025513"></a><a name="p538484025513"></a>70</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p5384040185512"><a name="p5384040185512"></a><a name="p5384040185512"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p338412406552"><a name="p338412406552"></a><a name="p338412406552"></a>Antiddos config</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p14384194011558"><a name="p14384194011558"></a><a name="p14384194011558"></a>openstack antiddos config</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p2038410407551"><a name="p2038410407551"></a><a name="p2038410407551"></a>-</p>
</td>
</tr>
<tr id="row83851840125516"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p2385134015520"><a name="p2385134015520"></a><a name="p2385134015520"></a>71</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p038564014559"><a name="p038564014559"></a><a name="p038564014559"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p73851740185512"><a name="p73851740185512"></a><a name="p73851740185512"></a>Open Antiddos</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p738564055511"><a name="p738564055511"></a><a name="p738564055511"></a>openstack antiddos open</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p123856402555"><a name="p123856402555"></a><a name="p123856402555"></a>-</p>
</td>
</tr>
<tr id="row18385740175517"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p4385340185516"><a name="p4385340185516"></a><a name="p4385340185516"></a>72</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p2385114025512"><a name="p2385114025512"></a><a name="p2385114025512"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p93851940165510"><a name="p93851940165510"></a><a name="p93851940165510"></a>Close Antiddos</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1385154045519"><a name="p1385154045519"></a><a name="p1385154045519"></a>openstack antiddos close</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p173858401559"><a name="p173858401559"></a><a name="p173858401559"></a>-</p>
</td>
</tr>
<tr id="row538554019559"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p2038516401559"><a name="p2038516401559"></a><a name="p2038516401559"></a>73</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p1638514019555"><a name="p1638514019555"></a><a name="p1638514019555"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p12385194011550"><a name="p12385194011550"></a><a name="p12385194011550"></a>Display Antiddos settings</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p5386164065512"><a name="p5386164065512"></a><a name="p5386164065512"></a>openstack antiddos show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p238634075510"><a name="p238634075510"></a><a name="p238634075510"></a>-</p>
</td>
</tr>
<tr id="row16386184013551"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p16387540185520"><a name="p16387540185520"></a><a name="p16387540185520"></a>74</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p19387144085510"><a name="p19387144085510"></a><a name="p19387144085510"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p73871840115514"><a name="p73871840115514"></a><a name="p73871840115514"></a>Update Antiddos settings</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p15387144095520"><a name="p15387144095520"></a><a name="p15387144095520"></a>openstack antiddos set</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p1387640115517"><a name="p1387640115517"></a><a name="p1387640115517"></a>-</p>
</td>
</tr>
<tr id="row10388840195516"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p838824017551"><a name="p838824017551"></a><a name="p838824017551"></a>75</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p9388340165520"><a name="p9388340165520"></a><a name="p9388340165520"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p838884035516"><a name="p838884035516"></a><a name="p838884035516"></a>Display Antiddos related task Details</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p1388164011555"><a name="p1388164011555"></a><a name="p1388164011555"></a>openstack antiddos task show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p13892402555"><a name="p13892402555"></a><a name="p13892402555"></a>-</p>
</td>
</tr>
<tr id="row11390540195519"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p239174018558"><a name="p239174018558"></a><a name="p239174018558"></a>76</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p439119403553"><a name="p439119403553"></a><a name="p439119403553"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p20391540135518"><a name="p20391540135518"></a><a name="p20391540135518"></a>List AntiDDos status</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p20391184005511"><a name="p20391184005511"></a><a name="p20391184005511"></a>openstack antiddos status list</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p20391440175518"><a name="p20391440175518"></a><a name="p20391440175518"></a>-</p>
</td>
</tr>
<tr id="row1939218408559"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p93921040125520"><a name="p93921040125520"></a><a name="p93921040125520"></a>77</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p12393740145511"><a name="p12393740145511"></a><a name="p12393740145511"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p1839384025520"><a name="p1839384025520"></a><a name="p1839384025520"></a>Display AntiDDos status</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p7393204015552"><a name="p7393204015552"></a><a name="p7393204015552"></a>openstack antiddos status show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p14393540115513"><a name="p14393540115513"></a><a name="p14393540115513"></a>-</p>
</td>
</tr>
<tr id="row139474015555"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p15394540155513"><a name="p15394540155513"></a><a name="p15394540155513"></a>78</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p17395104085515"><a name="p17395104085515"></a><a name="p17395104085515"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p203950408551"><a name="p203950408551"></a><a name="p203950408551"></a>List AntiDDos report</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p439594016551"><a name="p439594016551"></a><a name="p439594016551"></a>openstack antiddos daily</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p11396740195516"><a name="p11396740195516"></a><a name="p11396740195516"></a>-</p>
</td>
</tr>
<tr id="row1939614407555"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p13396194075516"><a name="p13396194075516"></a><a name="p13396194075516"></a>79</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p639613406550"><a name="p639613406550"></a><a name="p639613406550"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p113966406558"><a name="p113966406558"></a><a name="p113966406558"></a>List AntiDDos logs</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p18396194025514"><a name="p18396194025514"></a><a name="p18396194025514"></a>openstack antiddos logs</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p3396740115520"><a name="p3396740115520"></a><a name="p3396740115520"></a>-</p>
</td>
</tr>
<tr id="row639715409553"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p1839715408557"><a name="p1839715408557"></a><a name="p1839715408557"></a>80</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p203978403551"><a name="p203978403551"></a><a name="p203978403551"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p7397104045516"><a name="p7397104045516"></a><a name="p7397104045516"></a>List AntiDDos weekly protection statistics</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p53971540115520"><a name="p53971540115520"></a><a name="p53971540115520"></a>openstack antiddos weekly</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p103971740125514"><a name="p103971740125514"></a><a name="p103971740125514"></a>-</p>
</td>
</tr>
<tr id="row1739874010557"><td class="cellrowborder" valign="top" width="8.290000000000001%" headers="mcps1.1.6.1.1 "><p id="p7398104018557"><a name="p7398104018557"></a><a name="p7398104018557"></a>81</p>
</td>
<td class="cellrowborder" valign="top" width="17.32%" headers="mcps1.1.6.1.2 "><p id="p7398204015552"><a name="p7398204015552"></a><a name="p7398204015552"></a>AntiDDOS</p>
</td>
<td class="cellrowborder" valign="top" width="21.4%" headers="mcps1.1.6.1.3 "><p id="p5398204010558"><a name="p5398204010558"></a><a name="p5398204010558"></a>Display Antiddos alert settings</p>
</td>
<td class="cellrowborder" valign="top" width="19.36%" headers="mcps1.1.6.1.4 "><p id="p10406194016553"><a name="p10406194016553"></a><a name="p10406194016553"></a>openstack antiddos alert config show</p>
</td>
<td class="cellrowborder" valign="top" width="33.629999999999995%" headers="mcps1.1.6.1.5 "><p id="p17406440135511"><a name="p17406440135511"></a><a name="p17406440135511"></a>openstack antiddos alert config show --os-antiddos-api-version=2    This command is    supported only by    versions later than    python openstack    client3.9.0.</p>
</td>
</tr>
</tbody>
</table>

