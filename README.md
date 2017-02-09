# XTabLayout
This is a TabLayout. Its extra feature is to get the navigation bar icon out of his Parent.

（这是一个增强版本的TabLayout，它额外增加的功能是提供底部栏图标能溢出它的父类.）

#Picture
The Picture is dimiss.

#How to use
###Its usage is the same as TabLayout

    .setupWithViewPager(viewPager);//setting up this TabLayout with ViewPager
    
    .setBottomMargin(int dp);//set the bottomMargin --unit:dp
    
    .setTextSize(float sp);//set title size --unit:sp
    
    .addTab(new TabLayoutBuilder.ItemStatus(CharSequence title, @IdRes int drawableSelectorId, int normalTitleColor, int selectedTitleColor);//add tab to TabLayout
    
    .build();//show tabView to your screen
