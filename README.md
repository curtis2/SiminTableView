@(博客)
#android自定义view实现的柱状图

示例：
 

使用方法：

```
  ColumnarChart     barChart= (ColumnarChart) findViewById(R.id.bar_chart);
        //选中的柱子
        float userAtgroup=600;
         //最大的柱子
        float maxGroup=790;
        //柱子数值的比例数组
        float[] defaultRects=new float[]{300,215,475,500,535,615,655,690,690,740,790,715,660,600,520,470,400,255};
        barChart.setParamsDefult(defaultRects,userAtgroup,maxGroup);
```

 
