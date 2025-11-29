## Thông tin

Mỗi người sẽ có 1 file tex riêng để tự làm slide
Có file main.tex là file build chung

## Build
Mỗi người tự đẩy source mình lên mấy LaTeX online (gồm file mình và file main) để tự build

## LaTeX/Beamer
- Tạo 1 frame bẳng
```LaTeX
\begin{frame}
\frametitle{Title}
\framesubtitle{Subtitle}
<<content>>
\end{frame}
```

- Trong frame thì dùng các environment như enumerate, itemize, block, columns, figure, table
- Muốn hiện thứ tự slide trong frame thì dùng <...> như nếu muốn theo thứ tự tự động thì để <+->
ngay sau khai báo begin{environment}, nếu không tự động thì xem thêm \pause (phổ biến nhất), \uncover, \only, ...
