# calculator
devloped by hitaxi
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="fill_parent"
    android:layout_height="fill_parent" >

    <Button
        android:id="@+id/button1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignParentBottom="true"
        android:layout_alignParentLeft="true"
        android:layout_marginBottom="17dp"
        android:layout_marginLeft="16dp"
        android:text="%" />

    <Button
        android:id="@+id/button2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button1"
        android:layout_alignBottom="@+id/button1"
        android:layout_toRightOf="@+id/button1"
        android:text="0" />

    <Button
        android:id="@+id/button4"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button3"
        android:layout_alignParentRight="true"
        android:layout_toRightOf="@+id/button3"
        android:text="=" />

    <Button
        android:id="@+id/button3"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button2"
        android:layout_alignBottom="@+id/button2"
        android:layout_toRightOf="@+id/button2"
        android:text="." />

    <Button
        android:id="@+id/button5"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/button1"
        android:layout_alignLeft="@+id/button1"
        android:text="1" />

    <Button
        android:id="@+id/button6"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button5"
        android:layout_alignLeft="@+id/button2"
        android:text="2" />

    <Button
        android:id="@+id/button7"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button6"
        android:layout_toRightOf="@+id/button6"
        android:text="3" />

    <Button
        android:id="@+id/button8"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button7"
        android:layout_alignLeft="@+id/button4"
        android:layout_alignParentRight="true"
        android:text="+" />

    <Button
        android:id="@+id/button9"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/button5"
        android:layout_alignLeft="@+id/button5"
        android:text="4" />

    <Button
        android:id="@+id/button10"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button9"
        android:layout_toRightOf="@+id/button9"
        android:text="5" />

    <Button
        android:id="@+id/button11"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button10"
        android:layout_alignBottom="@+id/button10"
        android:layout_toRightOf="@+id/button10"
        android:text="6" />

    <Button
        android:id="@+id/button12"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button11"
        android:layout_alignLeft="@+id/button8"
        android:layout_alignParentRight="true"
        android:text="-" />

    <Button
        android:id="@+id/button13"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/button9"
        android:layout_alignLeft="@+id/button9"
        android:text="7" />

    <Button
        android:id="@+id/button14"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/button10"
        android:layout_toRightOf="@+id/button13"
        android:text="8" />

    <Button
        android:id="@+id/button15"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/button14"
        android:layout_alignBottom="@+id/button14"
        android:layout_toRightOf="@+id/button14"
        android:text="9" />

    <Button
        android:id="@+id/button16"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBottom="@+id/button15"
        android:layout_alignLeft="@+id/button12"
        android:layout_alignParentRight="true"
        android:text="*" />

    <Button
        android:id="@+id/button17"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/button13"
        android:layout_alignLeft="@+id/button13"
        android:layout_alignRight="@+id/button14"
        android:text="Ac" />

    <Button
        android:id="@+id/button18"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_above="@+id/button15"
        android:layout_alignParentRight="true"
        android:layout_toRightOf="@+id/button15"
        android:text="/" />

    <Button
        android:id="@+id/button19"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_centerVertical="true"
        android:layout_toLeftOf="@+id/button16"
        android:text="^" />

    <TextView
        android:id="@+id/textView1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/button17"
        android:layout_alignParentTop="true"
        android:layout_alignRight="@+id/button13"
        android:layout_marginTop="50dp"
        android:text="No1" />

    <TextView
        android:id="@+id/textView2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignLeft="@+id/textView1"
        android:layout_alignRight="@+id/textView1"
        android:layout_below="@+id/textView1"
        android:layout_marginTop="21dp"
        android:text="No2" />

    <EditText
        android:id="@+id/editText1"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/textView1"
        android:layout_alignBottom="@+id/textView1"
        android:layout_alignParentRight="true"
        android:ems="10"
        android:inputType="number" />

    <EditText
        android:id="@+id/editText2"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_alignBaseline="@+id/textView2"
        android:layout_alignBottom="@+id/textView2"
        android:layout_alignParentRight="true"
        android:ems="10"
        android:inputType="number" />
    
</RelativeLayout>
