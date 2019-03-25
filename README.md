# LearnLayout

线性布局linearlayout

最外层LinearLayout嵌套4个LinearLayout垂直排列：
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical">
    
每个LinearLayout中间写4个button或者textview组件，水平排列
    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal">

        <Button
            android:id="@+id/btn1"
            android:layout_width="99dp"
            android:layout_height="wrap_content"
            android:text="One,One" />

        <Button
            android:id="@+id/btn2"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="One,Two" />

        <Button
            android:id="@+id/btn3"
            android:layout_width="113dp"
            android:layout_height="wrap_content"
            android:text="One,Three" />

        <Button
            android:id="@+id/btn4"
            android:layout_width="110dp"
            android:layout_height="wrap_content"
            android:text="One,Four" />
    </LinearLayout>
    
Genymotion模拟器运行效果截图：

![image](https://github.com/grapeyu/LearnLayout/blob/master/images/搜狗截图20190325003254.jpg)

约束布局constraintlayout

Genymotion模拟器运行效果截图：

![image](https://github.com/grapeyu/LearnLayout/blob/master/images/搜狗截图20190325140533.jpg)

表格布局tablelayout

写几个TableRow，在其中嵌套TableView组件

TableRow>
        <TextView
            android:layout_width="20dp"
            android:layout_height="match_parent"
            android:gravity="center"
            android:layout_marginLeft="10sp"
            android:text=""/>

        <TextView
            android:padding="10sp"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Quit"/>

        <TextView
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text=""
            android:padding="10dp"/>
    </TableRow>

Genymotion模拟器运行效果截图：

![image](https://github.com/grapeyu/LearnLayout/blob/master/images/搜狗截图20190325144742.jpg)
