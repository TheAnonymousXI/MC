# Project ﷺ-V4

A Collection of bookmarks put together to make an over the tops client for all to use.

Bookmarklet:
#+BEGIN_SRC html 
javascript:(function()%7B%2F*%0A __     __   ______   ____    _____     __      _   _     _______   __    __   _____     ____       ___%0A%7C  %5C   %2F  %7C %7C  __  %7C %7C  _ %5C  %7C   __%7C   %7C  %7C    %7C %7C %7C %7C   %7C__   __%7C %7C  %7C  %7C  %7C %7C   __%7C   %7C  _ %5C     %2F _ %5C%0A%7C   %5C_%2F   %7C %7C %7C__%7C %7C %7C %7C %5C %7C %7C  %7C__    %7C  %7C_   %5C %5C_%2F %2F      %7C %7C    %7C  %7C__%7C  %7C %7C  %7C__    %7C %7C_%7C %7C   %7C %7C %7C_%7C%0A%7C         %7C %7C  __  %7C %7C %7C %7C %7C %7C   __%7C   %7C  _ %5C   %5C   %2F       %7C %7C    %7C   __   %7C %7C   __%7C   %7C   _%2F    %7C %7C  _%0A%7C  %7C%5C_%2F%7C  %7C %7C %7C  %7C %7C %7C %7C_%2F %7C %7C  %7C__    %7C %7C_%7C %7C   %7C %7C        %7C %7C    %7C  %7C  %7C  %7C %7C  %7C__    %7C  %7C    _ %7C %7C_%7C %7C _%0A%7C__%7C   %7C__%7C %7C_%7C  %7C_%7C %7C____%2F  %7C_____%7C   %7C____%2F    %7C_%7C        %7C_%7C    %7C__%7C  %7C__%7C %7C_____%7C   %7C__%7C   %7C_%7C %5C___%2F %7C_%7C%0A*%2F%0A%0Ajavascripts%3A%0A%0A(function() %7B%0A%09var currentPage %3D 1%3B%0A%09var numPages %3D 2%3B%0A%09var pages %3D %5B%0A%09%09%5B%7B%0A%09%09%09%09name%3A "Page 1"%2C%0A%09%09%09%09url%3A "js%3ATitle"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Mario Cursor"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B var style %3D document.createElement(%2527style%2527)%2C styleContent %3D document.createTextNode(%2527* %7B cursor%3A url(https%3A%2F%2Fl413.github.io%2FCursor-Changer%2Ficons%2Fmario.gif) 12 12%2C auto !important%7D%2527)%3B style.appendChild(styleContent )%3B var caput %3D document.getElementsByTagName(%2527head%2527)%3B caput%5B0%5D.appendChild(style)%3B %7D)()%3B"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Paintdrip Cursor"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B var style %3D document.createElement(%2527style%2527)%2C styleContent %3D document.createTextNode(%2527* %7B cursor%3A url(https%3A%2F%2Fl413.github.io%2FCursor-Changer%2Ficons%2Fpaint-pink.gif) 12 12%2C auto !important%7D%2527)%3B style.appendChild(styleContent )%3B var caput %3D document.getElementsByTagName(%2527head%2527)%3B caput%5B0%5D.appendChild(style)%3B %7D)()%3B"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Set Rotation to 0"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B%5B''%2C '-ms-'%2C '-webkit-'%2C '-o-'%2C '-moz-'%5D.map(function(prefix)%7Bdocument.body.style%5Bprefix %2B 'transform'%5D %3D 'rotate(0deg)'%3B%7D)%3B%7D())"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Set Rotation to 90"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B%5B''%2C '-ms-'%2C '-webkit-'%2C '-o-'%2C '-moz-'%5D.map(function(prefix)%7Bdocument.body.style%5Bprefix %2B 'transform'%5D %3D 'rotate(90deg)'%3B%7D)%3B%7D())"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Set Rotation to 180"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B%5B''%2C '-ms-'%2C '-webkit-'%2C '-o-'%2C '-moz-'%5D.map(function(prefix)%7Bdocument.body.style%5Bprefix %2B 'transform'%5D %3D 'rotate(180deg)'%3B%7D)%3B%7D())"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Set Rotation to 270"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B%5B''%2C '-ms-'%2C '-webkit-'%2C '-o-'%2C '-moz-'%5D.map(function(prefix)%7Bdocument.body.style%5Bprefix %2B 'transform'%5D %3D 'rotate(270deg)'%3B%7D)%3B%7D())"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Blank"%2C%0A%09%09%09%09url%3A "js%3ABlank"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Bookmarklet Maker"%2C%0A%09%09%09%09url%3A "https%3A%2F%2Fcaiorss.github.io%2Fbookmarklet-maker%2F"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "TheAnonymousXI's Website"%2C%0A%09%09%09%09url%3A "https%3A%2F%2Fgithub.com%2FTheAnonymousXI"%0A%09%09%09%7D%2C%0A%09%09%5D%2C%0A%09%09%5B%7B%0A%09%09%09%09name%3A "Page 2"%2C%0A%09%09%09%09url%3A "js%3ATitle"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Page Nucker"%2C%0A%09%09%09%09url%3A "javascript%3Avar KICKASSVERSION%3D'2.0'%3Bvar s %3D document.createElement('script')%3Bs.type%3D'text%2Fjavascript'%3Bdocument.body.appendChild(s)%3Bs.src%3D'%2F%2Fhi.kickassapp.com%2Fkickass.js'%3Bvoid(0)%3B"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Blur"%2C%0A%09%09%09%09url%3A "javascript%3A (function () %7B document.body.style.filter %3D 'blur(5px)'%3B %7D)()%3B"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Edit Webpage"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B  document.designMode%3D'on'%3B  const s%3Ddocument.createElement('style')%3B  s.innerHTML%3D%60body%3A%3Abefore%7Bcontent%3A'✏%25EF%25B8%258F Edit Mode (ESC to end)'%3Bz-index%3A64%3Bpadding%3A1em%3Bbackground%3Awhite%3Bcolor%3Ablack%3Bdisplay%3Ablock%3Bmargin%3A1em%3Bfont-size%3A30px%3Bborder%3A5px solid green%3B%7D%60%3B  document.body.appendChild(s)%3B  window.scrollTo(0%2C0)%3B  document.addEventListener('keyup'%2Ce %3D> %7B    if(e.key%3D%3D%3D'Escape')%7B      document.designMode%3D'off'%3B      s.remove()%3B      document.removeEventListener('keyup'%2Ce)%3B    %7D  %7D)%3B%7D)()%3B"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Show Password"%2C%0A%09%09%09%09url%3A "javascript%3A(function()%7B var IN%2CF%3BIN%3Ddocument.getElementsByTagName('input')%3B for(var i%3D0%3Bi<IN.length%3Bi%2B%2B)%7BF%3DIN%5Bi%5D%3B if(F.type.toLowerCase()%3D%3D'password')%7B try%7BF.type%3D'text'%7Dcatch(r)%7B var n%2CFa%3Bn%3Ddocument.createElement('input')%3B Fa%3DF.attributes%3Bfor(var ii%3D0%3Bii<Fa.length%3Bii%2B%2B)%7B var k%2Cknn%2Cknv%3Bk%3DFa%5Bii%5D%3Bknn%3Dk.nodeName%3Bknv%3Dk.nodeValue%3B if(knn.toLowerCase()!%3D'type')%7B if(knn!%3D'height'%26%26knn!%3D'width'%26!!knv)n%5Bknn%5D%3Dknv%7D%7D%3B F.parentNode.replaceChild(n%2CF)%7D%7D%7D%7D)()"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Blank"%2C%0A%09%09%09%09url%3A "js%3ABlank"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Blank"%2C%0A%09%09%09%09url%3A "js%3ABlank"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Blank"%2C%0A%09%09%09%09url%3A "js%3ABlank"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "Bookmarklet Maker"%2C%0A%09%09%09%09url%3A "https%3A%2F%2Fcaiorss.github.io%2Fbookmarklet-maker%2F"%0A%09%09%09%7D%2C%0A%09%09%09%7B%0A%09%09%09%09name%3A "TheAnonymousXI's Website"%2C%0A%09%09%09%09url%3A "https%3A%2F%2Fgithub.com%2FTheAnonymousXI"%0A%09%09%09%7D%2C%0A%09%09%5D%0A%09%5D%3B%0A%0A%09function createMenu() %7B%0A%09%09var menu %3D document.createElement("div")%3B%0A%09%09menu.setAttribute("style"%2C "position%3Afixed%3Btop%3A5px%3Bright%3A5px%3Bbackground-color%3A%23000%3Bcolor%3A%230f0 !important%3Bpadding%3A5px%3Bborder-radius%3A10px%3Bz-index%3A9999%3Bfont-family%3Amonospace !important%3Bfont-size%3A16px !important%3Bwidth%3A250px%3Bheight%3A600px%3B")%3B%0A%09%09menu.innerHTML %3D '<div style%3D"text-align%3Aright%3B"><button style%3D"background-color%3Ared !important%3Bpadding%3A5px !important%3Bborder-radius%3A5px !important%3Bborder%3Anone%3Bcursor%3Apointer%3B" onclick%3D"document.body.removeChild(this.parentNode.parentNode)%3B">X<%2Fbutton><%2Fdiv><h3 style%3D"color%3Ared !important%3Bmargin-top%3A0%3B">Project ﷺ - V4<%2Fh3>'%3B%0A%09%09var pageList %3D document.createElement("ul")%3B%0A%09%09pageList.setAttribute("style"%2C "list-style%3Anone%3Bpadding%3A0%3Bmargin%3A0%3B")%3B%0A%09%09for (var i %3D 0%3B i < pages%5BcurrentPage - 1%5D.length%3B i%2B%2B) %7B%0A%09%09%09var item %3D pages%5BcurrentPage - 1%5D%5Bi%5D%3B%0A%09%09%09var listItem %3D document.createElement("li")%3B%0A%09%09%09var link %3D document.createElement("a")%3B%0A%09%09%09link.setAttribute("href"%2C item.url)%3B%0A%09%09%09link.textContent %3D item.name%3B%0A%09%09%09listItem.appendChild(link)%3B%0A%09%09%09pageList.appendChild(listItem)%3B%0A%09%09%7D%0A%09%09menu.appendChild(pageList)%3B%0A%09%09var pageNav %3D document.createElement("div")%3B%0A%09%09pageNav.setAttribute("style"%2C "text-align%3Acenter%3B")%3B%0A%09%09for (var i %3D 1%3B i <%3D numPages%3B i%2B%2B) %7B%0A%09%09%09var button %3D document.createElement("button")%3B%0A%09%09%09button.setAttribute("style"%2C "margin%3A5px !important%3B border-radius%3A0px !important%3B")%3B%0A%09%09%09if (i %3D%3D%3D currentPage) %7B%0A%09%09%09%09button.textContent %3D "%5B" %2B i %2B "%5D"%3B%0A%09%09%09%7D else %7B%0A%09%09%09%09button.textContent %3D i%3B%0A%09%09%09%09button.addEventListener("click"%2C function(e) %7B%0A%09%09%09%09%09currentPage %3D parseInt(e.target.textContent)%3B%0A%09%09%09%09%09document.body.removeChild(menu)%3B%0A%09%09%09%09%09createMenu()%3B%0A%09%09%09%09%7D)%3B%0A%09%09%09%7D%09%0A%09%09%09pageNav.appendChild(button)%3B%0A%09%09%7D%0A%09%09menu.appendChild(pageNav)%3B%0A%09%09document.body.appendChild(menu)%3B%0A%09%7D%0A%09createMenu()%3B%0A%7D)()%3B%7D)()%3B
#+END_SRC
