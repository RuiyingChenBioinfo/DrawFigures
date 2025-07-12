# DrawFigures
The author acknowledge Dr. H.D. who pushed the author to collect all the scripts for drawing.

## Part 0: 基本配色的逻辑可以参考00.ColorPal.Summary.pptx

## Part 1: 几大金刚R包！！可与ggplot直接对接，与scale_color_manual()用法相似，谁用谁知道，谁用谁不后悔

viridis (https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html)

ggsci (https://cran.r-project.org/web/packages/ggsci/vignettes/ggsci.html)

## Part 2：我自己调理的R语言配色，这个方式适合要用很多个颜色且有lineage区别的图谱

fun_color_range1 <- colorRampPalette(c("#B850B1", "#ED8874", "#F4BE76"))

fun_color_range2 <- colorRampPalette(c("#46466A", "#5083A4", "#6ECACD"))

fun_color_range3 <- colorRampPalette(c("#357B6E", "#4FAC89", "#9ACE8F"))

fun_color_range4 <- colorRampPalette(c("#9c3538", "#e65a5d", "#f7a1b6"))

fun_color_range5 <- colorRampPalette(c("#82543A", "#987653", "#C8AB86"))

下面是取用方式，要取几个就取几个：

c(fun_color_range1(4), fun_color_range2(2), fun_color_range3(2), fun_color_range4(2))

## Part 3: Abode Illustrator里面统一所有x/y轴的线为黑色，且为0.5 pt（或者别的统一粗细），如果不统一就会显得丑

## Part 4：多收集已发表文献里使用的颜色，直接把pdf拉到Abode Illustrator打开吸取颜色即可

## Part 5：空间转录组离得近的颜色会区分不开细胞类型，这个可以用已经存在的色板+palo/spaco宝优化分布
