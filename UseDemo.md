# 使用案例

![](picture/shape_select_background.jpg)

```xml
<com.hjq.shape.view.ShapeButton
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:clickable="true"
    android:gravity="center"
    android:padding="10dp"
    android:text="填充色按压效果"
    android:textColor="@android:color/white"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="20dp"
    app:shape_solidColor="#5A8DDF"
    app:shape_solidPressedColor="#AA5A8DDF" />

<com.hjq.shape.view.ShapeButton
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:clickable="true"
    android:gravity="center"
    android:padding="10dp"
    android:text="渐变色按压效果"
    android:textColor="@android:color/white"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_endColor="#ED58FF"
    app:shape_radius="20dp"
    app:shape_solidPressedColor="#5A8DDF"
    app:shape_startColor="#49DAFA" />

<com.hjq.shape.view.ShapeButton
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:enabled="false"
    android:gravity="center"
    android:padding="10dp"
    android:text="填充色禁用效果"
    android:textColor="@android:color/white"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="20dp"
    app:shape_solidColor="#5A8DDF"
    app:shape_solidDisabledColor="#BBBBBB" />

<com.hjq.shape.view.ShapeButton
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:clickable="true"
    android:gravity="center"
    android:padding="10dp"
    android:text="边框色按压效果"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="20dp"
    app:shape_solidPressedColor="#5A8DDF"
    app:shape_strokeColor="#5A8DDF"
    app:shape_strokeWidth="1dp"
    app:shape_textColor="#5A8DDF"
    app:shape_textPressedColor="@android:color/white" />

<com.hjq.shape.view.ShapeButton
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:enabled="false"
    android:gravity="center"
    android:padding="10dp"
    android:text="边框色禁用效果"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="20dp"
    app:shape_strokeColor="#5A8DDF"
    app:shape_strokeDisabledColor="#BBBBBB"
    app:shape_strokeWidth="1dp"
    app:shape_textColor="@android:color/black"
    app:shape_textDisabledColor="#BBBBBB" />
```

![](picture/shape_shadow_background.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:clickable="true"
    android:gravity="center"
    android:paddingTop="30dp"
    android:paddingBottom="30dp"
    android:text="默认阴影颜色"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="10dp"
    app:shape_shadowColor="#20000000"
    app:shape_shadowSize="10dp"
    app:shape_solidColor="#FFFFFF" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:paddingTop="30dp"
    android:paddingBottom="30dp"
    android:text="修改阴影颜色"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="10dp"
    app:shape_shadowColor="#AA5A8DDF"
    app:shape_shadowSize="10dp"
    app:shape_solidColor="#FFFFFF" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:clickable="true"
    android:gravity="center"
    android:paddingTop="30dp"
    android:paddingBottom="30dp"
    android:text="阴影偏移效果"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="10dp"
    app:shape_shadowColor="#50000000"
    app:shape_shadowOffsetX="5dp"
    app:shape_shadowOffsetY="5dp"
    app:shape_shadowSize="10dp"
    app:shape_solidColor="#FFFFFF" />
```

![](picture/shape_select_text_gradient.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="文本水平渐变效果"
    android:textSize="14sp"
    app:shape_textEndColor="#ED58FF"
    app:shape_textGradientOrientation="horizontal"
    app:shape_textStartColor="#49DAFA" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="文本垂直渐变效果"
    android:textSize="14sp"
    app:shape_textEndColor="#ED58FF"
    app:shape_textGradientOrientation="vertical"
    app:shape_textStartColor="#49DAFA" />
```

![](picture/shape_select_compound_button.jpg)

```xml
<com.hjq.shape.view.ShapeCheckBox
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:background="@null"
    android:gravity="center"
    android:padding="10dp"
    android:text="我是自定义按钮样式的 CheckBox"
    android:textSize="14sp"
    app:shape_buttonCheckedDrawable="@drawable/checkbox_checked_ic"
    app:shape_buttonDisabledDrawable="@drawable/checkbox_disable_ic"
    app:shape_buttonDrawable="@drawable/checkbox_normal_ic" />

<com.hjq.shape.view.ShapeRadioButton
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:background="@null"
    android:gravity="center"
    android:padding="10dp"
    android:text="我是自定义按钮样式的 RadioButton"
    android:textSize="14sp"
    app:shape_buttonCheckedDrawable="@drawable/radiobutton_checked_ic"
    app:shape_buttonDisabledDrawable="@drawable/radiobutton_disable_ic"
    app:shape_buttonDrawable="@drawable/radiobutton_normal_ic" />
```

![](picture/shape_rectangle.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="矩形实线边框内部无填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="矩形虚线边框内部无填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_dashGap="5dp"
    app:shape_dashWidth="10dp"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="矩形实线边框-内部填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_solidColor="#ff00ffff"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="矩形虚线边框-内部填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_dashGap="5dp"
    app:shape_dashWidth="10dp"
    app:shape_solidColor="#ff00ffff"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />
```

![](picture/shape_rectangle_round.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆角矩形-只有边框"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="5dp"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆角矩形-只有内部填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="5dp"
    app:shape_solidColor="#8000ff00" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆角矩形-有边框有填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="5dp"
    app:shape_solidColor="#8000ff00"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆角矩形-左边圆角为一个半圆弧"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_bottomLeftRadius="20dp"
    app:shape_solidColor="#8000ff00"
    app:shape_topLeftRadius="20dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆角矩形-左右两边都是半圆弧"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="20dp"
    app:shape_solidColor="#8000ff00" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆角矩形-左右两边都是半圆弧-带边框"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_radius="20dp"
    app:shape_solidColor="#8000ff00"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />
```

![](picture/shape_rectangle_gradient.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="垂直线性渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_angle="-45"
    app:shape_centerColor="#8000ff00"
    app:shape_centerX="0.5"
    app:shape_centerY="0.4"
    app:shape_endColor="#1000ff00"
    app:shape_startColor="#ff00ff00"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="水平线性渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_angle="0"
    app:shape_centerColor="#8000ff00"
    app:shape_centerX="0.5"
    app:shape_centerY="0.5"
    app:shape_endColor="#ff00ff00"
    app:shape_startColor="#1000ff00"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="对角线线性渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_angle="45"
    app:shape_centerColor="#8000ff00"
    app:shape_centerX="0.5"
    app:shape_centerY="0.5"
    app:shape_endColor="#1000ff00"
    app:shape_startColor="#ff00ff00"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="径向渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_angle="0"
    app:shape_centerX="0.5"
    app:shape_centerY="0.5"
    app:shape_endColor="#ff00ff00"
    app:shape_gradientRadius="20dp"
    app:shape_gradientType="radial"
    app:shape_startColor="#0000ff00"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="扫描渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="rectangle"
    app:shape_angle="0"
    app:shape_centerX="0.5"
    app:shape_centerY="0.5"
    app:shape_endColor="#0000ff00"
    app:shape_gradientType="sweep"
    app:shape_startColor="#ff00ff00"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />
```

![](picture/shape_oval.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆-边框"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="oval"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆-填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="oval"
    app:shape_solidColor="#800000ff" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆-边框填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="oval"
    app:shape_solidColor="#800000ff"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="线性渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="oval"
    app:shape_angle="-90"
    app:shape_centerColor="#80ff0000"
    app:shape_centerX="0.5"
    app:shape_centerY="0.8"
    app:shape_endColor="#ffff0000"
    app:shape_gradientType="linear"
    app:shape_startColor="#00ff0000" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="径向渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="oval"
    app:shape_centerColor="#80ff0000"
    app:shape_centerX="0.5"
    app:shape_centerY="0.5"
    app:shape_endColor="#10ff0000"
    app:shape_gradientRadius="80dp"
    app:shape_gradientType="radial"
    app:shape_startColor="#ffff0000" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="扫描渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="oval"
    app:shape_centerColor="#80ff0000"
    app:shape_centerX="0.5"
    app:shape_centerY="0.6"
    app:shape_endColor="#20ff0000"
    app:shape_gradientRadius="20dp"
    app:shape_gradientType="sweep"
    app:shape_startColor="#ffff0000" />
```

![](picture/shape_ring.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="环内填充"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="ring"
    app:shape_innerRadiusRatio="4"
    app:shape_thicknessRatio="4"
    app:shape_solidColor="#80ff0000" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆环边框"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="ring"
    app:shape_innerRadiusRatio="4"
    app:shape_thicknessRatio="4"
    app:shape_strokeWidth="2dp"
    app:shape_strokeColor="#ffff00ff" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="圆环边框"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="ring"
    app:shape_innerRadiusRatio="4"
    app:shape_thicknessRatio="4"
    app:shape_solidColor="#80ff0000"
    app:shape_strokeWidth="2dp"
    app:shape_strokeColor="#ffff00ff" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="线性渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="ring"
    app:shape_innerRadiusRatio="4"
    app:shape_thicknessRatio="4"
    app:shape_angle="45"
    app:shape_centerColor="#80ff0000"
    app:shape_endColor="#ffff0000"
    app:shape_startColor="#00ff0000"
    app:shape_gradientType="linear" />

<com.hjq.shape.view.ShapeTextView
    android:layout_width="200dp"
    android:layout_height="200dp"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="扫描渐变"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="ring"
    app:shape_innerRadiusRatio="4"
    app:shape_thicknessRatio="4"
    app:shape_centerColor="#80ff0000"
    app:shape_endColor="#00ff0000"
    app:shape_startColor="#ffff0000"
    app:shape_gradientType="sweep" />
```

![](picture/shape_line.jpg)

```xml
<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="实线"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="line"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp"/>

<com.hjq.shape.view.ShapeTextView
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:layout_margin="10dp"
    android:gravity="center"
    android:padding="10dp"
    android:text="虚线"
    android:textColor="@android:color/black"
    android:textSize="14sp"
    app:shape="line"
    app:shape_dashGap="5dp"
    app:shape_dashWidth="10dp"
    app:shape_strokeColor="#ffff0000"
    app:shape_strokeWidth="1dp"/>
```
