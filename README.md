# kaka-grid 提示插件

#### 属性（template里使用）

|命令|提示内容|
|---|------|
|vue-grid|输出kaka-grid标签|
|grid-tree-columns|标签内：树形结构标签属性|
|grid-columns|标签内：columns属性|
|grid-records|标签内：records属性|
|grid-theme|标签内：theme属性带常用样式|
|grid-hide-header|标签内：隐藏表头属性|
|grid-read-only|标签内：只读属性|
|grid-check-cascade|标签内：级联|
|grid-span-body-options|标签内span-body-options属性|
|grid-single-selection|标签内：single-selection属性|
|grid-frozen-col-count|标签内：frozen-col-count属性|
|grid-border-mode-[none\|content-border\|grid-border]|标签内：边框线设置|
|grid-border-mode-border-color|标签内：边框线设置颜色|
|grid-border-mode-border-width|标签内：边框线设置宽度|
| ---| ---|
|grid-@load|标签内：load属性|
|grid-@cellselect|标签内：cellselect属性|
|grid-@buttonclick|标签内：buttonclick属性|
|grid-@getRecords|标签内：getRecords属性|
|grid-@hasRecords|标签内：hasRecords属性|
|grid-@cellcheck|标签内：cellcheck属性|
|grid-@celluncheck|标签内：celluncheck属性|
|grid-@checkall|标签内：checkall属性|
|grid-@uncheckall|标签内：unheckall属性|
|grid-@paste|标签内：paste属性(粘贴)|
|grid-@cellchange|标签内：cellchange属性|

#### 函数（script内使用）

|命令|提示内容|
|---|-------|
|grid-init|grid初始化函数|
|grid-fn-load|@load函数|
|grid-fn-cellselect|@cellselect函数|
|grid-fn-paste|@paste多行粘贴函数|
|grid-fn-cellchange|@cellchange函数|

#### columns（script内使用）

|命令|提示内容|
|---|-------|
|grid-col-normal|普通简洁列|
|grid-col-normal-full|普通多属性列|
|grid-col-id|序号列|
|grid-col-status|svg状态显示列|
|grid-col-line-button|行内按钮|
|grid-col-checkBox|行内单选框|
|grid-col-line-input-editor|行内编辑1|
|grid-col-line-lookup-editor|行内编辑2|
|grid-col-line-text-area-editor|行内编辑3|