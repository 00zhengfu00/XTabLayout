# XTabLayout
This is a TabLayout. Its extra feature is to get the navigation bar icon out of his Parent.

（这是一个增强版本的TabLayout，它额外增加的功能是提供底部栏图标能溢出它的父类.）

#Picture
<img src="https://github.com/sltpaya/XTabLayout/blob/master/info.gif"  width = "540" height = "960" alt="picture"/>

#How to use
###Its usage is the same as TabLayout
    
    //ViewPager
    ViewPager viewPager = (ViewPager) findViewById(R.id.xxx);
    viewPager.setAdapter(xxx);
    
    //TabLayoutBuilder
    TabLayoutBuilder tabLayout = (TabLayoutBuilder) findViewById(R.id.xxx);
    
    tabLayout.setupWithViewPager(viewPager);//setting up this TabLayout with ViewPager
    
    tabLayout.setBottomMargin(int dp);//set the bottomMargin --unit:dp
    
    tabLayout.setTextSize(float sp);//set title size --unit:sp
    
    tabLayout.addTab(new TabLayoutBuilder.ItemStatus(CharSequence title, @IdRes int drawableSelectorId, int normalTitleColor, int selectedTitleColor);//add tab to TabLayout
    
    tabLayout.build();//show tabView to your screen
