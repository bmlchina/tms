# 6.区域管理
考虑到城市特殊区域对一些车型有限行，为了避免配载后因为限行而无法配送的情况。我们增加了禁行区的功能。根据实际情况将不同的禁行区在地图上画出来，在我的车辆详情页中，设置当前车辆可行驶的禁行区。在配载订单时就不会将无法配送的订单分配给当前司机。

## 6.1区域设定
规划禁行区：

创建禁行区步骤：
设置“区域名称”：必填项，根据需要填写区域名称，限制20个字。
规划禁行区域：点击右下角多边形按钮在地图上画出多边形。鼠标左键点击确定一个点，当确定最后一个点时，鼠标左键双击，结束画图。
创建区域：点击“创建区域”按钮，即可创建禁行区。
经纬度列表显示画图时每个点的经纬度。当点击“清空当前数据”按钮时，清空当前页面上所有数据。

## 6.2区域列表
显示当前商户规划出的所有禁行区，可以通过区域名称进行查询。

鼠标左键双击可以打开当前禁行区的详情页，显示禁行区所限定的范围。可以修改当期禁行区的启用状态，点击“提交”即可。
