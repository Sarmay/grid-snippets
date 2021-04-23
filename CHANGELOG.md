# 更新日志


## [2021-04-23：更新内容]

- 增加grid-fn-resize 表格大小自适应
- 增加grid-fn-makeVisibleGridCell 按索引移动到可视区域
- 增加grid-fn-makeVisibleCell 按行列移动到可视区域

      makeVisibleGridCell 和 makeVisibleCell 都不会出发select_cell 事件，这两个只是让滚动条滚到目标单元格的位置，换个角度说就是让单元格呈现在显示区域内 

- 增加grid-fn-headerValues 设置表头复选框是否全选或取消勾选
- 增加grid-fn-expandToKey 获取字段索引
- 增加grid-fn-selectCellRange 选中单元格(会触发select_cell 事件)
- 增加grid-fn-focusCell 设置单个单元格焦点(会触发select_cell 事件)
- 增加grid-fn-getRecordStartRowByRecordIndex 根据索引获取行号
- 增加grid-fn-selection.range 获取焦点最小单元格
- 增加grid-fn-invalidate 刷新表格第一种方法
- 增加grid-fn-refresh 刷新表格第二种方法
- 增加grid-fn-fireSelectedEvent 刷新表格第三种方法
- 增加grid-fn-frozenColCount 固定前N行
- 增加grid-fn-singleSelection 只让单选单元格
- 增加grid-fn-expandAll 展开父子节点
- 增加grid-fn-collapseAll 折叠父子节点
- 增加grid-fn-getRowRecord 根据行号获取行数据


## [2020-08-26：更新内容]

- 增加grid-col-switch 行内滑块开关

## [2020-08-04：更新内容]

- 增加columns提示
- 修改bug

## [2020-08-03：更新内容]

- 修改bug