# Relay-computers-of-George-Stibitz
                                                 George-Stibitz的中繼計算機

貝爾電話實驗室成立於1925年，是貝爾系統的基礎研究設施。
因此，開始了一個機構，該機構已成為物理學，化學和現代科學其他領域前沿基礎研究和令人興奮的研究的代名詞
在接下來的幾十年裡，有許多發明家在這個激動人心的地方做大量的研究，並獲得了諾貝爾獎。
計算機領域的許多發明也將在這裡進行，讓我們只提及第一個邏輯方案與二極體(1942年)，點晶體管(1947年)，第一個完全晶體管計算機(TRADIC,1955年)，
第一調製 解調器(1960年)，第一個單晶片32位處理器(1980年),操作系統UNIX(1969),程式設計語言C(1973)和C++(1983年)等。
1937年11月的一個深夜，貝爾實驗室的研究數學家George Stibitz(George Stibitz的傳記)結束工作回家時，從貝爾儲藏室拿了兩個電話繼電器，一個手電筒燈泡、一根電線和一個乾電池。
在家裡，他坐在廚房桌子後面，開始組裝一個簡單的邏輯裝置，包含了上述部件和開關組成，由煙草錫製成。
他很快有了一個裝置，它被證明是第一個繼電器二進位加器，其中一個燈泡表示二進位數位"1"和一個未發光的燈泡，代表二進位數位"0"。
他的妻子Dorothea以「廚房桌子」命名為K-model。
第二天，Stibitz將K-model帶到實驗室向同事展示，他們推測了在繼電器中構建全尺寸計算機的可能性。
他的同事推斷，任何使用二進位算術的實用中繼電腦都可能需要數百台繼電器，因此它比當時在實驗室使用的商業機械計算機體積更大，成本更高。
 
但George Stibitz意識到，繼電器計算機可以執行的不僅僅是一個計算，而是一系列計算，繼電器電路可以指導順序，並根據需要存儲臨時結果。
具體來說，它可以執行複數乘法和除法所需的操作序列:貝爾實驗室其他地方的研究人員經常與濾波器和放大器進行兩種數學運算長距離電路的設計。
在1930年代的實驗室中，一大堆人類“電腦”使用商用機械計算器計算出複數商和乘積。
計算本身非常簡單:複雜的乘法需要大約六個簡單的算術運算，而複雜的除法需要大約十幾個運算，每個運算都需要臨時存儲幾個中間結果。

 George Stibitz不知道同時間在Berlin，Konrad Zuse跟他幾乎在做同樣的事情。
 然而，George Stibitz確實知道，Claude Shannon在麻省理工學院讀研究生期間，也研究了符號邏輯與二進制中繼電路的對應關係。
 Shannon寫了他的研究生論文(發表於1938年)，然後去了貝爾實驗室，在那裡，他和George Stibitz學習了彼此的工作。但Shannon並沒有積極參與Stibitz電腦的設計。
 顯然，使用中繼來實現二進位邏輯的想法在 20 世紀 30 年代末很常見。(日本也有類似的發現)。

當Stibitz第一次向公司高管展示他的K-model電腦時,他們並不印象深刻。沒有煙火，沒有香檳，他後來記得。
然而，不到一年之後，貝爾的高管們改變了對George Stibitz發明的看法。
做出這個決定的一個重要因素是貝爾面臨越來越大的壓力，要求找到解決其日益複雜的數學問題的方法。
公司同意資助建造一個大型的Stibitz發明實驗模型。
Stibitz 於1938年2月完成了設計，1939年4月,貝爾的開關工程師Samuel Williams開始建造該機器。
最終產品於10月準備就緒，1940 年 1 月 8 日首次投入運行,並一直使用到 1949 年。
由於貝爾實驗室在戰爭期間製造了其他中繼計算機，它的名字從最初的複數計算機改為1型。費用約為20000美元。
最初，複數電腦只執行複雜的乘法和除法，但後來的簡單修改使它能夠加法和減法。
它使用大約 400-450 個二進位繼電器、6-8 個面板和 10 個稱為「橫桿」的多位置多極繼電器來臨時存儲數位。
機器使用小數點,小數點固定在每個數字的開頭。
在內部,四個二進位繼電器編碼每個數位,使用表示十進位數位 n 的 n=3 二進位碼的代碼;這簡化了數位攜帶和減法的問題(超過三個二進位號碼十進制現在仍然被稱為"Stibitz代碼")。
機器在其寄存器中處理十位數位,但顯示並列印了八位答案(範圍??0.99999999999.它使用「字首」表示法:即運算符在計算機中鍵控之前對算術運算進行鍵控。
例如,要將兩個複數 (2+3i) 乘以 (4+5i),操作員將輸入(請參閱鍵盤的上部圖): M +.2 +i .3 +.4 -i .5 =                                                                 
字母M表示乘法(鍵盤中的字母D表示除法)。請注意四個數位中的每個數位之前的小數點的位置。
機器實際上將計算 (0.3+0.5i) x (0.4-0.2i),並列印答案0.07000000_i 0.22000000。
運算符必須相應地縮放結果(乘以 100)。一個簡單的加法大約需要100 mS,而2個複數的乘法大約需要45秒。
計算單元有 4 個寄存器,與輸入/輸出單元完全分離,這是一個特殊的終端(參見附近的照片)。
計算機本身被保存在實驗室的一個外在的房間里,很少有人見過它。
操作員使用三台經過修改的電傳機(鍵盤和列印設備)之一遠端訪問它,通過多線總線連接到處理器並放置在其他位置,但無法同時工作。

Stibitz 進一步發展了遠端、多路訪問計算機的想法。
1940年9月11日,美國數學會在新罕布希爾州漢諾威的達特茅斯學院開會,在紐約貝爾實驗室大樓以北幾百英里處,那裡是複數計算機。
Stibitz 安排通過電話線(28 線電傳式電纜)將電腦連接到安裝在那裡的電傳式裝置。
複數計算機運行良好,毫無疑問,它讓使用它的人印象深刻。
許多美國最傑出的數學家以及後來領導重要計算項目的人(如John von Neumann, John Mauchly, Norbert Wiener and Garrett Birkhoff)出席了會議。
Dartmouth的演示預示了現代遠端計算時代,但這種類型的遠端訪問在十年內沒有重複。

複數計算機不可程式設計。繼電器電路的組合永久控制其操作順序。
這些繼電器的類型與用於處理數位的繼電器的類型相同,但計算機沒有單獨的、定義明確的部件來處理計算序列的"控制"(後來貝爾實驗室的計算機做到了)。
在複雜數計算機建成後,貝爾實驗室才出現了可程式設計性的概念,因為其構建者發現其基本計算元素受到其聯姻的不當限制,以控制將之與複雜算術捆綁在一起的電路。
(除了複雜的算術,他們試圖讓機器執行多項式算術,其中複雜算術是一個特例。但機器被限制太多。)

複數電腦的成功鼓勵Stibitz提出更雄心勃勃的設計,包括通過穿孔磁帶修改計算機操作的能力。
起初,實驗室拒絕了他的建議,但隨著美國在1941年12月進入第二次世界大戰,貝爾實驗室將重點轉向軍事專案,涉及的計算比和平時期的研究更多。他們戰時的成就大多在模擬計算機的設計上。
但他們也建造了5台用於軍事目的的數位中繼計算機,在戰爭結束後又製造了一台供自己使用的數位中繼計算機,使總共7台數字計算機計算複數計算機。
這些用於軍事用途的計算機中,第一個是中繼插值器,於1943年安裝在華盛頓特區,後來被稱為型號II。
它由 440 個繼電器和 7 個數位的記憶體容量組成。乘法速度為4秒(通過重複加法乘法)。
它主要解決了與指揮防空火力有關的問題,通過執行一系列算術運算,通過紙帶插入提供給機器的函數值。
像複數計算機一樣,它是一種特殊用途的機器;然而,它的算術序列不是中繼計算機永久有線,而是由「公式磁帶」(五通道紙帶)黏在一個迴圈。
因此,不同的磁帶允許人們使用不同的插值方法。除了插值之外,模型二不能做太多工作,
但由於插值是一個能夠解決科學和工程中的許多問題的過程,機器在戰爭結束很久之後被其他政府機構忙於工作。
接下來的兩台機器,由Stibitz設計是彈道計算機和錯誤探測器馬克22(後來被稱為型號III和IV),是相同的機器,
第一個安裝在1944年,在布利斯堡,得克薩斯州,第二個在1945年初在華盛頓(每台成本65000美元)。
它們包含大約 1400 個繼電器,記憶體容量為 10 個數位。乘法速度為1秒(按表查找乘法)。這些機器還使用紙帶進行數據和公式輸入,算術序列由紙帶迴圈提供。
與型號II一樣,第三和第四型號也解決了與高射炮瞄準和跟蹤有關的問題。
然而,它們是更精密的機器,不僅能夠進行插值,而且能夠評估描述目標飛機和防空殼路徑的彈道方程。
另一張紙帶指示機器要評估的哪些功能。因此,模型 III 和 N 是貝爾實驗室第一個具有一定程度的通用可程式設計性的數位計算機,儘管兩者都不是完全通用的計算機。
它們的記憶體和算術單元具有適度的功能:只有六位十進位的精度數位,每台機器的記憶體為10個數位。

該系列中最大的計算機,最後一台由Stibitz設計,是型號V,其中貝爾實驗室在1946年和1947年為軍方製作了兩份副本。
這是一個巨大的(重量10噸)和非常昂貴(500000美元)的機器。每個包含超過九千個繼電器和處理用科學記數表示的數位。
存儲可以容納多達30個數位,紙磁帶閱讀器提供程式步驟和數位數據。
乘法速度 0.8 秒模型 V 設計最有趣的方面是,它有兩個獨立的算術單元,每個單元都能夠作為具有自己記憶體寄存器和輸入輸出設備的獨立電腦運行。
小規模問題可以在機器上成對運行,從而節省時間,而更大的問題可能會接管兩個處理器。與每個處理器(使用現代術語)相關的是 15 個記憶體寄存器,整個電腦總共 30 個。主控制單元根據一個或兩個處理器的可用性指示指令。
此控制單元與處理器中的控制單元分開,該控制單元指示算術、記憶體和輸入/輸出操作序列;它控制了控制,可以這麼說。(Stibitz 將其稱為"超級分支"功能。
因此,在一個非常真實的意義上,模型V有現在所謂的"操作系統",一個控制單元,監督和管理通過計算機的工作流程。

除了程式設計能力,後來的貝爾電腦強調非凡的可靠性。
繼電器用作邏輯和記憶體操作的基本元素,有間歇性故障的傾向。
如果一塊灰塵在兩個繼電器觸點之間出現,該迴路將失敗,儘管繼電器的其餘部分正常。
幾個迴圈後,塵埃顆粒可能會鬆弛,之後一切都會恢復正常。因此,整個計算可能關閉,在診斷會話期間不會顯示任何機器故障。

貝爾的工程師設計了計算機電路,在計算的每一步都檢查自己。
電路的設計不僅用於加法、減法、存儲數等;他們還被設計來檢查自己是否正確地做了這些事情，並以其他方式停止機器。
貝爾的工程師在設計電話電路時也遵循了經驗,這些電路在通常惡劣的環境中不得不在無人值守的情況下長時間工作。
這些電路的設計是由半熟練的技術人員修理的;如果每次電話線停機或客戶電話都死時,必須給工程師打電話,電話服務將非常昂貴。
貝爾實驗室模型 II 到 VI 使用一個系統,其中不是四個,而是七個二進位繼電器編碼每個十進位數位。他們被分成兩組,兩組和五個接力;十進位碼如下所示:

貝爾實驗室稱這個系統為「雙基」符號,因為繼電器的重量為一或五。實際上,它不是這些數字基礎的組合;相反,它是一個七位混合十進位碼。
所有的貝爾實驗室中繼計算機都用十進位算術工作。一條特殊電路檢查,發現每個十進位數位只有兩個繼電器通電。
另一個電路檢查每個組只有一個繼電器打開,這防止了兩個單獨的錯誤相互抵消,儘管某些異常故障組合可能未被檢測到。

Relay computers:中繼計算機
diodes:二極體
point transistor:點晶體管
fully transistor computer:完全晶體管計算機
modem:調製解調器
single-chip 32-bit processor:單晶片32位處理器
relays binary adder:繼電器二進位加器
filter:濾波器
amplifier:放大器
Complex Number Computer:複數計算機
Relay Interpolator:中繼插值器
Ballistic Computer:彈道計算機
Error Detector Mark 22:錯誤探測器馬克22

