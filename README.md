# _reset.scss

```
/* RESET */

html, body, div, span, applet, object, iframe, h1, h2, h3, h4, h5, h6, p, blockquote, pre, a, abbr, acronym, address, big, cite, code, del, dfn, em, img, ins, kbd, q, s, samp, small, strike, strong, sub, sup, tt, var, b, u, i, center, dl, dt, dd, ol, ul, li, fieldset, form, label, legend, table, caption, tbody, tfoot, thead, tr, th, td, article, aside, canvas, details, embed, figure, figcaption, footer, header, hgroup, menu, nav, output, ruby, section, summary, time, mark, audio, video {
    margin: 0;
    padding: 0;
    border: 0;
    font-size: 100%;
    font: inherit;
    vertical-align: baseline; }
  
  /* HTML5 display-role reset for older browsers */
  
  article, aside, details, figcaption, figure, footer, header, hgroup, menu, nav, section {
    display: block; }
  
  body {
    line-height: 1; }
  
  ol, ul {
    list-style: none; }
  
  blockquote, q {
    quotes: none; }
  
  blockquote {
    &:before, &:after {
      content: '';
      content: none; } }
  
  q {
    &:before, &:after {
      content: '';
      content: none; } }
  
  table {
    border-collapse: collapse;
    border-spacing: 0; }

img { 
	max-width: 100%; /* 適應 & 伸縮 */
	height: auto; /* 適應 & 伸縮 */
  vertical-align: middle; /* 圖片會預留 2-3px 在下面 */
}
*, *::before, *::after { /* 全域 border box > 不用算內距 */
	box-sizing: border-box;
}
a{
    text-decoration: none;
}
ul{
    padding: 0px;
}
p{
    padding: 0px;
    margin: 0px;
}

/* RESET-end */
```
