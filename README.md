  # 水厂矾耗量预测
  :blush:本项目使用matlab的神经网络工具箱对水厂的`原水流量`，`原水浊度`，`原水PH`，`单位耗矾流量`的数据进行训练，<br/>
  * 自变量为：`原水流量`，`原水浊度`，`原水PH`
  * 因变量为：`单位耗矾流量`
  * 神经网络参数：
   * 输入神经元个数：１
   * 隐含层数：１
   * 隐含层神经元个数：５５
   * 输出神经元个数：１
神经网络训练好后，将网络参数导出，并使用JS重写此神经网络，使其能够运行在浏览器上。使用HTML做了简单的UI。<br/><br/>
  ### 成品展示:metal:<br/>
  [展示](http://www.buildce.com/demo/sc.html "展示")，代码见`神经网络预测水厂矾耗JS代码.html`文件。 
