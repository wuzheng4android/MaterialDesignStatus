# MaterialDesignStatusBar
���ô��ڼ���4.4�汾��״̬������ɫ


**����**

1.������res��Դ�ļ�Ŀ¼�½���values-19Ŀ¼,ֻҪϵͳ�汾����kitkatϵͳ���Լ���ȡ��Ŀ¼�µ�style�ļ�,��Ĭ�ϵ�values�µ�style�е�������ʽ������values-19Ŀ¼�µ�style�ļ���,��Ҫ���������������

        <item name="android:windowTranslucentNavigation" >true</item>
        
        <item name="android:windowTranslucentStatus">true</item>


2.��mainactivity�Ĳ����еĸ���ǩ�����������²���

<pre><code>
android:fitsSystemWindows="true"

</code></pre>


3.Ȼ����������:

<pre><code>
        if (Build.VERSION.SDK_INT >= Build.VERSION_CODES.KITKAT) {
            SystemBarTintManager tintManager = new SystemBarTintManager(this);
            tintManager.setStatusBarTintEnabled(true);
            tintManager.setStatusBarTintResource(R.color.colorPrimaryDark);
        }
</code></pre>

![Alt text](https://github.com/hzy87email/StatusBarColor/blob/master/screenshot/demo1.png)

![Alt text](https://github.com/hzy87email/StatusBarColor/blob/master/screenshot/demo2.png)