# Self-Contained
 Azure pipeline üzerinden Self-Contained  olarak projeyi publish etme hakkında küçük bir örnek

# Self-Contained olarak ayarlamak
publish blogunda ki <b>arguments</b> parametresine <b>-r win-x64 --self-contained true </b> parametresini eklemeniz yeterli olacaktır.<br/><br/>
<b>-r win-x64 / win-x86 ...      :</b> hangi platform için çıktı alacağınızı <br/>
<b>--Self-contained true/false   :</b> Gereksinimlerin yüklenip yüklenmeyeceğini belirler.  <br/><br/>
 arguments: '--configuration $(BuildConfiguration) --output $(build.artifactstagingdirectory) -r win-x64 --self-contained true' <br/> 
 
