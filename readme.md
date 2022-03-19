在grid-system.css中
修改min-width的数值，调整发生自适应的临界值

@media (min-width: 768px) {
.container {
width: 750px;
}
}

@media (min-width: 992px) {
.container {
width: 970px;
}
}

@media (min-width: 1200px) {
.container {
width: 1170px;
}
}


.col-xs-1~12，屏幕宽度12等份，可以修改数量和左浮动所占的百分比调整布局

sm lg可以混合使用，比如左边的1当屏幕很大的时候，通过媒体查询占据lg-6
