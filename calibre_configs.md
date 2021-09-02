Click 'convert' menu button


# Look & feel > Styling > Extra CSS
@font-face {
  font-family: "DroidFont", "MsYaHei", serif, sans-serif;
  src: url(res:///ebook/fonts/DroidSansFallback.ttf)
}


# Structure detection > Detect chapters at
//*[re:test(., "^\s*[第卷][0123456789一二三四五六七八九十零〇百千两]*[章回部节節集卷].*", "i")]


# Table of Contents > Level 1 TOC
//*[re:test(@class, "第(一|二|三|四|五|六|七|八|九|十|百|○)+(回|章|篇)", "i")]


