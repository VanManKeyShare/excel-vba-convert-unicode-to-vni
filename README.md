Function UNICODE_TO_VNI(DATA As String)

Dim C As String, I As Long
   For I = 1 To Len(DATA)
      C = Mid(DATA, I, 1)
      Select Case C
         Case ChrW$(97): C = "a"
         Case ChrW$(225): C = "aù"
         Case ChrW$(224): C = "aø"
         Case ChrW$(7843): C = "aû"
         Case ChrW$(227): C = "aõ"
         Case ChrW$(7841): C = "aï"
         Case ChrW$(259): C = "aê"
         Case ChrW$(7855): C = "aé"
         Case ChrW$(7857): C = "aè"
         Case ChrW$(7859): C = "aú"
         Case ChrW$(7861): C = "aü"
         Case ChrW$(7863): C = "aë"
         Case ChrW$(226): C = "aâ"
         Case ChrW$(7845): C = "aá"
         Case ChrW$(7847): C = "aà"
         Case ChrW$(7849): C = "aå"
         Case ChrW$(7851): C = "aã"
         Case ChrW$(7853): C = "aä"
         Case ChrW$(101): C = "e"
         Case ChrW$(233): C = "eù"
         Case ChrW$(232): C = "eø"
         Case ChrW$(7867): C = "eû"
         Case ChrW$(7869): C = "eõ"
         Case ChrW$(7865): C = "eï"
         Case ChrW$(234): C = "eâ"
         Case ChrW$(7871): C = "eá"
         Case ChrW$(7873): C = "eà"
         Case ChrW$(7875): C = "eå"
         Case ChrW$(7877): C = "eã"
         Case ChrW$(7879): C = "eä"
         Case ChrW$(111): C = "o"
         Case ChrW$(243): C = "où"
         Case ChrW$(242): C = "oø"
         Case ChrW$(7887): C = "oû"
         Case ChrW$(245): C = "oõ"
         Case ChrW$(7885): C = "oï"
         Case ChrW$(244): C = "oâ"
         Case ChrW$(7889): C = "oá"
         Case ChrW$(7891): C = "oà"
         Case ChrW$(7893): C = "oå"
         Case ChrW$(7895): C = "oã"
         Case ChrW$(7897): C = "oä"
         Case ChrW$(417): C = "ô"
         Case ChrW$(7899): C = "ôù"
         Case ChrW$(7901): C = "ôø"
         Case ChrW$(7903): C = "ôû"
         Case ChrW$(7905): C = "ôõ"
         Case ChrW$(7907): C = "ôï"
         Case ChrW$(105): C = "i"
         Case ChrW$(237): C = "í"
         Case ChrW$(236): C = "ì"
         Case ChrW$(7881): C = "æ"
         Case ChrW$(297): C = "ó"
         Case ChrW$(7883): C = "ò"
         Case ChrW$(117): C = "u"
         Case ChrW$(250): C = "uù"
         Case ChrW$(249): C = "uø"
         Case ChrW$(7911): C = "uû"
         Case ChrW$(361): C = "uõ"
         Case ChrW$(7909): C = "uï"
         Case ChrW$(432): C = "ö"
         Case ChrW$(7913): C = "öù"
         Case ChrW$(7915): C = "öø"
         Case ChrW$(7917): C = "öû"
         Case ChrW$(7919): C = "öõ"
         Case ChrW$(7921): C = "öï"
         Case ChrW$(121): C = "y"
         Case ChrW$(253): C = "yù"
         Case ChrW$(7923): C = "yø"
         Case ChrW$(7927): C = "yû"
         Case ChrW$(7929): C = "yõ"
         Case ChrW$(7925): C = "î"
         Case ChrW$(273): C = "ñ"
         Case ChrW$(65): C = "A"
         Case ChrW$(193): C = "AÙ"
         Case ChrW$(192): C = "AØ"
         Case ChrW$(7842): C = "AÛ"
         Case ChrW$(195): C = "AÕ"
         Case ChrW$(7840): C = "AÏ"
         Case ChrW$(258): C = "AÊ"
         Case ChrW$(7854): C = "AÉ"
         Case ChrW$(7856): C = "AÈ"
         Case ChrW$(7858): C = "AÚ"
         Case ChrW$(7860): C = "AÜ"
         Case ChrW$(7862): C = "AË"
         Case ChrW$(194): C = "AÂ"
         Case ChrW$(7844): C = "AÁ"
         Case ChrW$(7846): C = "AÀ"
         Case ChrW$(7848): C = "AÅ"
         Case ChrW$(7850): C = "AÃ"
         Case ChrW$(7852): C = "AÄ"
         Case ChrW$(69): C = "E"
         Case ChrW$(201): C = "EÙ"
         Case ChrW$(200): C = "EØ"
         Case ChrW$(7866): C = "EÛ"
         Case ChrW$(7868): C = "EÕ"
         Case ChrW$(7864): C = "EÏ"
         Case ChrW$(202): C = "EÂ"
         Case ChrW$(7870): C = "EÁ"
         Case ChrW$(7872): C = "EÀ"
         Case ChrW$(7874): C = "EÅ"
         Case ChrW$(7876): C = "EÃ"
         Case ChrW$(7878): C = "EÄ"
         Case ChrW$(79): C = "O"
         Case ChrW$(211): C = "OÙ"
         Case ChrW$(210): C = "OØ"
         Case ChrW$(7886): C = "OÛ"
         Case ChrW$(213): C = "OÕ"
         Case ChrW$(7884): C = "OÏ"
         Case ChrW$(212): C = "OÂ"
         Case ChrW$(7888): C = "OÁ"
         Case ChrW$(7890): C = "OÀ"
         Case ChrW$(7892): C = "OÅ"
         Case ChrW$(7894): C = "OÃ"
         Case ChrW$(7896): C = "OÄ"
         Case ChrW$(416): C = "Ô"
         Case ChrW$(7898): C = "ÔÙ"
         Case ChrW$(7900): C = "ÔØ"
         Case ChrW$(7902): C = "ÔÛ"
         Case ChrW$(7904): C = "ÔÕ"
         Case ChrW$(7906): C = "ÔÏ"
         Case ChrW$(73): C = "I"
         Case ChrW$(205): C = "Í"
         Case ChrW$(204): C = "Ì"
         Case ChrW$(7880): C = "Æ"
         Case ChrW$(296): C = "Ó"
         Case ChrW$(7882): C = "Ò"
         Case ChrW$(85): C = "U"
         Case ChrW$(218): C = "UÙ"
         Case ChrW$(217): C = "UØ"
         Case ChrW$(7910): C = "UÛ"
         Case ChrW$(360): C = "UÕ"
         Case ChrW$(7908): C = "UÏ"
         Case ChrW$(431): C = "Ö"
         Case ChrW$(7912): C = "ÖÙ"
         Case ChrW$(7914): C = "ÖØ"
         Case ChrW$(7916): C = "ÖÛ"
         Case ChrW$(7918): C = "ÖÕ"
         Case ChrW$(7920): C = "ÖÏ"
         Case ChrW$(89): C = "Y"
         Case ChrW$(221): C = "YÙ"
         Case ChrW$(7922): C = "YØ"
         Case ChrW$(7926): C = "YÛ"
         Case ChrW$(7928): C = "YÕ"
         Case ChrW$(7924): C = "Î"
         Case ChrW$(272): C = "Ñ"
      End Select
      UNICODE_TO_VNI = UNICODE_TO_VNI + C
   Next I
End Function
