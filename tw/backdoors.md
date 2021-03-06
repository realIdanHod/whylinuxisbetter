---
layout: default
identifier: backdoors
category: tw
title: "你的軟體將不再含有惡意的後門程式"
---

「封閉原始碼」（非開放的）和「開放原始碼」的差異在於（你猜是什麼呢？）它們的「程式碼」是否公開。呃，好吧，為什麼我會關心這個呢？「程式碼」或「原始碼」就像是每個軟體的<b>配方</b>，可以想成蛋糕的配方。當你買了一個蛋糕，你沒有辦法想出它正確的配方（雖然你可以猜出零星的資訊，像是「這裡撒了一些椰子粉」）。如果一家蛋糕店把它超受歡迎的起司蛋糕的配方公開，那麼它很快就要從市場上消失了，因為大家可以在家自己做，而不用去店裡買。同樣地，微軟不公開 Windows 和其他軟體的配方，也就是「原始碼」，這是很自然的，因為這是它賺錢的工具。

問題在於，微軟能夠在不讓我們知道的情況下，把<b>任何他們想要的東西</b>放進配方裡。如果他們想要增加一段這樣的程式碼：「如果電腦在每個月的 12 號這天有連上網路，就把上個月已經下載過的所有檔案作成一個清單，然後透過網路傳回給微軟。」微軟可能沒有這麼做，但是，由於每件事都是不公開的、看不見的和秘密進行的，<b>你怎麼知道呢</b>？

前陣子（2008 年十月），許多中國 Windows 使用者（他們幾乎都是購買盜版的 Windows）發現他們的電腦有些不尋常的現象：每個小時，他們的螢幕畫面都會變成全黑長達數秒。雖然不會讓你不能做事，但也足以讓你抓狂。微軟植入了一小段程式碼（在配方中增添一種原料）：「如果發現這是份盜版的 Windows，就讓螢幕在每小時內都會變黑數秒。」盜版軟體不是這件事的重點：毋庸置疑，盜版軟體是不好的。重點在於，這些使用者的 Windows 會在他們不知情的情況下自動更新（自動更新通常是用來修正 bug 和增加新功能），同時也不知道這些更新會對他們的系統造成什麼樣的影響。沒有人知道。

修改開放原始碼軟體的內容是一個比較公開的過程。很明顯的，所有的配方都是公開的。如果你不會去瞭解程式碼，那麼這件事對你來說沒有太大的影響。但瞭解程式的人則可以去觀看它並且提出任何意見。每當有人想修改原始碼，所有開發人員都能看見被修改的部份（喂老兄你瘋了嗎，為什麼加入能監控使用者鍵盤輸入的程式碼？）。即使某個軟體元件的整組維護人員都瘋了，並且在原始碼的各處植入了具有侵略性的功能，團隊以外的人可以取得程式碼、移除所有不好的部份、創造一個全新的版本並且讓全世界知道修改了哪些地方。這就是<b>開放</b>。

這就是為什麼你能夠相信，開放原始碼軟體的背後沒有其他惡意程式：整個社群會緊盯著所有配方。




 