# Sublime Text 配置

1. 下载：[Sublime Text](https://www.sublimetext.com/)

2. 自定义配置：

   ```JSON
   // Preferences -> Setting
   {
     // 字体
   	"font_face": "Source DejaVu",
     // 字体大小
   	"font_size": 13,
     // 偏爱的颜色样式
   	"color_scheme": "Mariana.sublime-color-scheme",
   	"theme": "auto",
     // 行间距
   	"line_padding_top": 1.5,
   	"line_padding_bottom": 1.5,
   }
   
   ```

   ```JSON
   // Preferences -> Customize Color Theme
   {
   	"variables":
   	{
   		"bg_color": "hsl(0, 0%, 15%)",
   		"font_color": "hsl(0, 0%, 67%)"
   	},
   	"globals":
   	{
       // 默认文字颜色
   		"foreground": "var(font_color)",
       // 背景颜色
   		"background": "var(bg_color)"
   	},
   	"rules":
   	[
   	]
   }
   ```