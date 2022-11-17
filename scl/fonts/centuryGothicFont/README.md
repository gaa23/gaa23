WEBFONT Century Gothic: All folders contain different type and unicode range. Below the description:

Normal: unicode-range: U+0020-F003

GOTHIC: unicode-range: U+0020-2215

GOTHICB: - BOLD unicode-range: U+0020-2215

GOTHICBO: - BOLD unicode-range: U+0020-F003

GOTHICBI: - BOLD ITALIC unicode-range: U+0020-F003

GOTHICI: - ITALIC unicode-range: U+0020-2215


Add this codes to head tag:

<!DOCTYPE html>
<html>
    <br>  
    <head>
        <style>

            @import url('https://raw.githubusercontent.com/gaa23/gaa23/main/scl/fonts/centuryGothicFont/GOTHIC/Century%20Gothic.css');
            @import url('https://raw.githubusercontent.com/gaa23/gaa23/main/scl/fonts/centuryGothicFont/GOTHICB/Century%20Gothic.css');
            @import url('https://raw.githubusercontent.com/gaa23/gaa23/main/scl/fonts/centuryGothicFont/GOTHICB0/Century%20Gothic.css');
            @import url('https://raw.githubusercontent.com/gaa23/gaa23/main/scl/fonts/centuryGothicFont/GOTHICBI/Century%20Gothic.css');
            @import url('https://raw.githubusercontent.com/gaa23/gaa23/main/scl/fonts/centuryGothicFont/GOTHICI/Century%20Gothic.css');
            @import url('https://raw.githubusercontent.com/gaa23/gaa23/main/scl/fonts/centuryGothicFont/normal/Century%20Gothic.css');
            


            body {
                font-family: 'Century Gothic';
            }

</style>
</head>
