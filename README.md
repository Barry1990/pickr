
<h3 align="center">
    在原有的Simonwep/pickr功能上改了点样式
</h3>

<h3 align="center">
  <img alt="Demo" src="https://user-images.githubusercontent.com/30767528/53578134-4e297e80-3b77-11e9-9d74-4d2ed547c274.gif"/>
</h3>

<h4 align="center">
  <a href="https://barry1990.github.io/pickr/">改造之后的Demo</a>
</h4>

```
    // 安装
    npm install git+https://github.com/Barry1990/pickr.git
    
    import '@simonwep/pickr/dist/themes/tenda.min.css';
    import Pickr from '@simonwep/pickr';

    // html
    <div id="pickr-parent" style="margin-left: 17px;" >
      <div id="pickr">选择颜色</div>
    </div>


    // js
    this.pickr = Pickr.create({
      el: '#pickr',
      theme: 'tenda',
      container: '#pickr-parent',
      swatches: [
        'rgba(244, 67, 54, 1)',
        'rgba(156, 39, 176, 0.9)',
        'rgba(63, 81, 181, 0.8)',
        'rgba(3, 169, 244, 0.7)',
        'rgba(0, 150, 136, 0.75)',
      ],
      components: {
        preview: true,
        opacity: true,
        hue: true,
        interaction: {
          input: true,
          save: true
        }
      }
    });
 ```   
