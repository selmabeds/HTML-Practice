**#All references:**
[CSS References](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)


**#1. Selectors (see files)**

**#2. Fonts**
        font-size: 10pt (px,in,cm,mm,pc,em,ex, xx-small, xx-large), no space allowed

        font-family: Arial

        font-variant: small-caps

        font-style: italic (ovlique, normal)

        font-weight: bolder (lighter, bold, normal) OR specify as multiple

        text-decoration: line-through (overline, underline, none)

        etc.


**#3. Lists**

        i. ul Unlisted

        Style, decorate a marker: 
            list-style-image: url('somepicture.gif');

                Ex.: 
                <style>
                    ul {
                    list-style-image: url(‘somepicture.gif');
                    }
                </style>


        ii. ol Organized list

        Style:
            decimal (1,2,3,4)
            upper-alpha (A,B,C,D)
            lower-alpha (a,b,c,d)
            upper-roman (I,II,III,IV)
            lower-roman (i,ii,iii,iv)


**#4. Colors (3 ways)**

        color:name

        rgb(n1,n2,n3)

        #123456

**#5. Alignments**

        p.indent(text-indent:0.5in) OR % value

        p.align(text-align:centre) OR left,right,justify

        img{float:right} 
            Text flows around another element
            float:Clear to turn off
        


**#6. Borders**

        Box Model:
        Outer Edge
            Margin, Border, Padding
                Inner Edge
                    Content

