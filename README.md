# rankbrain

## Hướng dẫn tổng quan

Nếu bạn nghiêm túc về SEO, bạn CẦN tối ưu RankBrain

Tại sao ?

Nó thật sự tốt, Google gần đây thông báo rằng RankBrain là tín hiệu xếp hạng quan trọng thứ ba của Google

Và nó đang trở lên quan trọng từng ngày.

Trong hướng dẫn này bạn sẽ học mọi thứ bạn cần để biết về thuật toán RankBrain của Google.lét đu ịt

Bạn không có thời gian để đọc toàn bộ hướng dẫn này ?

Đừng lo lắng. TÔi gửi cho bạn một bản copy mà bạn có thể đọc nó 1 cách thuận tiện cho bạn. Tải ở đây : [PDF](https://app.monstercampaigns.com/c/vmliigrsoljooeiop3di/)


# Chương 1

## Google RankBrain: Giải thích trực quan
RankBrain là một trí tuệ nhân tạo mà Google sử dụng để sắp xếp các kết quả tìm kiếm. Nó cũng giúp Google sử lý và hiểu các truy vấn tìm kiếm.

Vậy điều gì làm RankBrain khác biệt?

Trước RankBrain, 100% thuật toán của Google được viết bằng tay.
Vì thế quá trình sử lý được diễn ra như thế này:

![1](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/1_2_google-engineers.png)



Tất nhiên, Các kĩ sư con người vẫn làm việc trên thuật toán. Nhưng ngày nay, RankBrain cũng làm điều đó trong background.

Nói ngắn gọn, RankBrain tự điều chỉnh thuật toán

Tùy thuộc vào từ khóa, RankBrain sẽ tăng hay giảm bớt tầm quan trọng của backlinks, sự mới mẻ của nội dung, chiều dài của nội dung,
cơ quan tên miền, etc.

Sau đó, Nó nhìn vào cách người tìm kiếm của Google tương tác với kết quả tìm kiếm mới. Nếu người dùng thích thuật toán mới hơn nó sẽ giữ lại. Nếu không, RankBrain sẽ quay lại thuật toán cũ.

Đây là phần điên rồ nhất:

Google yêu cầu một nhóm kỹ sư xác định trang tốt nhất cho một kết quả tìm kiếm và họ cũng yêu cầu RankBrain.

Và RankBrain thông minh hơn các kỹ sư 10 %.

![2](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/1_4_accuracy.png)

Tóm lại, RankBrain hoạt động. Và nó ở đây để chặn lại.

Bây giờ cái bạn đã thấy tổng quan về RankBrain. Hãy tìm hiểu sâu hơn cách nó hoạt động.


# Chương 2

## RankBrain có 2 công việc chính:

1. Hiểu các truy vấn tìm kiếm (các từ khóa)
2. Đo lường cách con người tương tác với kết quả (sự hài lòng của người dùng)

Hãy phân tích từng phần. 

## Cách mà RankBrain hiểu bất kì thứ gì bạn tìm kiếm.

Một vài năm trước, Google có một vấn đề:

15% từ khóa mà mọi người đã nhập vào google chưa từng thấy trước đây.

15% có lẽ nhìn không nhiều. Nhưng khi bạn sử lý hàng tỷ tìm kiếm một ngày, điều đó có nghĩa là 450 triệu từ khóa làm Google bối rối mỗi ngày.

Trước RankBrain, Google sẽ quét các trang để xem nó có chứa các từ khóa mà ai đó tìm kiếm không.

Nhưng bởi vì  những từ khóa này là thương hiệu mới, Google không có đầu mối về cái mà người tìm kiếm cần. Vì vậy nó đoán.

Ví đụ, Giả sử bạn tìm kiếm “the grey console developed by Sony”. Google sẽ tìm các trang có chứa các điều kiện "grey", “console”, “developed” và “Sony”.

![3](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_2_search-keywords.png)

Ngày nay, RankBrain thực sự hiểu cái mà bạn yêu cầu. Và cung cấp kết quả tìm kiếm chính xác 100% :
![4](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_3_rankbrain-results.png)

Không tệ nhỉ.

Những gì đã thực sự thay đổi? Trước đây , Google sẽ cố gắng kết hợp các từ trong truy vấn tìm kiếm của bạn với các từ trong một trang.

Ngày nay, RankBrain cố gắng tìm hiểu ý của bạn.Bạn biết đó, giống như một con người vậy.
Làm như thế nào? Bằng cách kết hợp những từ khóa chưa bao giờ thấy trước đây với các từ khóa Google đã thấy trước đây.

Ví dụ, Google RankBrain có thể nhận thấy rằng có rất nhiều người tìm kiếm “grey console developed by Nintendo”.

Và nó học được rằng những người tìm kiếm “grey console
developed by Nintendo” muốn nhìn thấy tập hợp các kết quả về tay cầm chơi game.

Vì thế khi ai đó tìm kiếm “the grey console developed
by Sony”, RankBrain đưa lên kết quả tương tự cho từ khóa nó đã biết  (“grey console developed by Nintendo”).

Vì vậy nó cho kết quả về các tay cầm. Trong trường hợp này là PlayStation.

![5](https://cdn-backlinko.pressidium.com/wp-content/uploads/2018/01/2_4_rankbrain-method.png)

Một ví dụ khác: một thời gian trước khi Google công bố một bài đăng trên blog cách mà họ sử dụng máy móc để học cách hiểu rõ hơn về ý định của người tìm kiếm:

![6](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_5_google-open-source-blog.png)

Trong bài viết này họ miêu tả một công nghệ được gọi là “Word2vec” biến từ khóa thành khái niệm

Ví dụ, Google nói công nghệ này “ hiểu rằng Pháp và Paris là liên quan giống như Berlin và Đức (Thủ đo và quốc gia) và không giống như Madrid và Italy”.

![7](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_6_country-and-capital.png)

Mặc dù bài đăng này không nói cụ thể về RankBrain,
RankBrain có khả năng sử dụng công nghệ tương tự.

Nói ngắn gọn: Google RankBrain vượt trội so với so sánh từ khóa đơn giản. Nó biến từ khóa tìm kiến của bạn thành các khái niệm và cố gắng tìm thấy các trang bao gồm các khái niệm đó.

Ở chapter 3 Tôi sẽ cho bạn thấy làm thế nào điểu này thay đổi cách chúng ta nên nghiên cứu từ khóa SEO. Nhưng đầu tiên, hãy xem phần thú vị nhất của RankBrain.

## Cách RankBrain đo lường sự hài lòng của người dùng

Chắc chắn rồi, RankBrain có thể  đâm vào để tìm hiểu từ khóa mới.Và nó cũng có thể tự tinh chỉnh thuật toán

Nhưng câu hỏi lớn ở đây là: Khi RankBrain cho bạn thấy một tập hợp các kết quả tìm kiếm, làm cách nào để biết liệu chúng có thật sự tốt không?

Vâng nó quan sát:

![8](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_7_rankbrain-uses-ux-signals.png)

Nói cách khác, RankBrain cho ta thấy một tập hợp các kết quả tìm kiếm mà nó nghĩ bạn sẽ thích. Nếu nhiều người thích một trang cụ thể trong kết quả, nó sẽ cho trang đó tăng hạng.

Và nếu bạn không thích trang đó? Nó sẽ bỏ trang đó và thay thế nó bằng một trang khác. Và lần tới ai đó tìm kiếm với từ khóa đó (hoặc một thuật ngữ tương tự) họ sẽ thấy nó hoạt động như thế nào.

Cái mà RankBrain quan sát chính xác?

Nó rất chú ý tới các mà bạn tương các với kết quả tìm kiếm. Đặc biệt, nó xem xét:
    - Tỷ lệ click có tổ chức
    - Thời gian sống
    - Tỉ lệ thoát
    - tỉ lệ quay lại trang
    
Đây gọi là tín hiệu trải nghiêm người dùng (Tín hiệu UX ).

Hãy xem xét một ví dụ:

Bạn căng cơ lưng sau khi chơi tennis. Vì thế bạn tìm kiếm “bị căng cơ lưng” trên Google.

Giống như hầu hết mọi người, bạn click vào kết quả đầu tiên. Không may, phần mở đầu có nội dung ngoài lề (“Lưng của bạn là một nhóm cơ quan trọng...”).

Vì thế bạn ấn quay lại và kiểm tra kết quả thứ 2:

![9](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_9_pogo-stick-effect-1.png)


Cái này không tốt lắm. Nó có các lời khuyên chung chung như “ Nghỉ ngơi và chườm đá lưng của bạn”.

Vì thế bạn lại ấn quay lại một làm nữa và ấn vào kết quả thứ 3.
![10](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_10_pogo-stick-effect-2.png)


Bingo! Đó là hết quả chính xác cái mà bạn đang tìm kiếm.

Vì vậy thay vì ấn trở lại, bạn mất 5 phút đọc qua các cách trị liệu vật lý của trang. Và bởi vì bạn có những gì bạn muốn bạn không trở lại kết quả tìm kiếm.

Việc quay lại và ra được gọi là “Pogo-sticking”. Đó là một cái gì đó mà RankBrain rất coi trọng hành động đó.

Nếu Google được thông báo rằng mọi người nhanh chóng rời khỏi trang và click vào một kết quả tìm kiếm khác, điều đó gửi một thông báp mạnh mẽ tời Google:
“Trang đó không tốt!”.
![11](https://cdn-backlinko.pressidium.com/wp-content/uploads/2017/11/2_11_pogo-stick-effect-3.png)

Và nết Google được thông báo rằng nhiều người dừng pogo-sticking lên một kết quả cụ thể, nó sẽ đẩy trang đó lên để trang đó tìm kiếm dễ dàng hơn.

Tôi sẽ nói nhiều hơn nữa về tín hiệu UX trong Chapters 4
và 5. Nhưng bây giờ, là thời gian để tôi cho bạn thấy cách mà RankBrain thay đổi cách hoạt động nghiên cứu từ khóa.

## Chương 3: Nghiên cứu từ khóa trong Thế Giới RankBrain
Như các bạn đã thấy, Google giờ đã có thể hiểu được những mục tiêu đằng sau 1 từ khóa.
Vậy liệu rằng những cách nghiên cứu từ khóa truyền thống sẽ vô dụng?
Không hề!
Nó có nghĩa là bạn có thể cần phải tinh chỉnh quá trình nghiên cứu từ khóa của bạn để thân thiện với RankBrain hơn.

Và đây là cách:

##  Loại bỏ những từ khóa dài (Chúng đã vô dụng rồi)

Những từ khóa dài đã vô dụng rồi
Quay trở về ngày ý nghĩa mà chúng ta tạo hàng trăm các trang khác nhau... với mỗi trang đều được tối ưu xoay quanh 1 từ khóa khác nhau.
Ví dụ, bạn tạo 1 trang được tối ưu cho "công cụ nghiên cứu từ khóa tốt nhất". Và 1 trang khác tối ưu cho "công cụ tốt nhất cho nghiên cứu từ khóa"

Và Google cũ sẽ xếp hạng chúng dựa theo những từ khóa dài tương ứng của chúng.
Ngày nay, RankBrain hiểu rằng những cụm từ này đơn thuần chỉ là 1. Vì vậy chúng hiển thị những kết quả tìm kiếm gần như tương tự nhau.
Nói 1 cách ngắn gọn, việc tối ưu những từ khóa dài không có nghĩa gì nữa.
Vậy chúng ta nên làm gì thay thế? tiếp tục đọc phần dưới nào...


## Tối ưu xung quanh những từ khóa có độ dài trung bình
Thay vì những từ khóa dài, tôi khuyên bạn nên tối ưu nội dung xung quanh những từ khóa có độ dài trung bình.
Những từ khóa có độ dài trung bình là những cụm từ trung bình. Chúng nó lượng tìm kiếm nhiều hơn những từ khóa dài trung bình của bạn. Nhưng chúng lại không quá khó để cạnh tranh.
Ví dụ, đây là 1 tập các từ khóa xung quanh chủ đề "Paleo Diet". Các cụm từ ở giữa là những từ khóa có độ dài trung bình.
Khi bạn tối ưu trang của bạn xung quanh 1 từ khóa độ dài trung bình ( và khiến trang web đó trở nên tuyệt vời). RankBrain sẽ tự động xếp hạng bạn cho cụm từ đó... và hàng nghìn những từ khóa tương tự.
Nói 1 cách ngắn gọn, tôi khuyên bạn nên tối ưu trang của bạn xung quanh 1 từ khóa đơn.
(Hãy đảm bảo đó là 1 từ khóa có độ dài trung bình)
Sau đó, hãy để RankBrain xếp hạng trang đơn của bạn với nhiều từ khóa khác liên quan
Vậy 1 ví dụ về quá trình này trong thực tế thì sao?
## 1 ví dụ về việc nghiên cứu từ khóa và SEO On-Page trong thế giới RankBrain
1 thời gian trước tôi đã quyết định sẽ viết review về tất cả các công cụ SEO tôi đã sử dụng.

Kết quả là? SEO Tools: Danh sách đầy đủ.

Do nội dung của tôi cung cấp 1 lượng lớn giá trị trên từng trang đơn, nó được xếp hàng trong top 5 với từ khóa đích (độ dài trung bình) của tôi: SEO Tools.
Nhưng quan trong hơn đó là, RankBrain hiểu rằng trang web của tôi nói về các khái niệm như "công cụ SEO", "phần mềm SEO", "các công cụ nghiên cứu từ khóa" vân vân
Đó là lí do tại sao trang đơn này được xếp hạng cho 1800 từ khóa khác nhau (dựa theo SEMrush): Đó là sức mạnh của việc tối ưu nội dung hấp dẫn xung quanh 1 từ khóa đơn có độ dài trung bình.

## Chương 4: Làm thế nào để tối ưu các thẻ tiêu đề và miêu tả cho CTR
Như bạn đã thấy ở chương 1, organic CTR là 1 dấu hiệu xếp hạng quan trọng của RankBrain
Câu hỏi đặt ra là: làm thế nào để bạn có thể làm cho người khác click vào kết quả của bạn?
Đúng rồi, đó chính xác những gì tôi muốn làm rõ trong chương này

## Đóng gói các cảm xúc vào thẻ Tiêu đề 
Không còn nghi ngờ gì nữa: các tiêu đề có cảm xúc sẽ có nhiều lượt click hơn.
Đây là điều mà những người viết quảng cáo đã biết vài năm nay rồi. Và trong những năm gần đây, những dữ liệu cho thấy ý tưởng này đang dần quay trở lại. Trong thực tế, CoSchedule tìm thấy 1 sự liên quan rất rõ rệt giữa  những tiêu đề có cảm xúc cao với những chia sẻ trên mạng xã hội.
Giá trị của cảm xúc
Ví dụ, đây là 1 tag tiêu đề được tối ưu SEO 1 cách cơ bản.

#### Mẹo về năng suất: Cách hoàn thành nhiều hơn
không tệ nhỉ. Nhưng nó có vẻ còn thiếu 1 vài thứ để thúc đẩy mọi người click vào nó.
Đây là cách bạn có thể biến tag tiêu đề trên thành 1  thứ có nhiều cảm xúc hơn ( mà vẫn giữ nó thân thiện với SEO)

####Đè bẹp danh sách việc cần làm của bạn với 17 mẹo năng suất này

Không phải lúc nào việc tạo ra những tiêu đề với nhiều cảm xúc sẽ đem lại hiệu quả. Nhưng bạn nên làm bất cứ khi nào có thể.

## Thêm các cặp dấu ngoặc vào cuối tiêu đề của bạn
Đây là 1 trong những cách ưa thích để hack CTR mà tôi luôn sử dụng
Đầu tiên tôi khám phá ra mẹo này từ 1 bài nghiên cứu HubSpot và Outbrain đã thực hiện vài năm trước
Trong nghiên cứu đó, họ đã phân tích 3.3 triệu tiêu đề. Và họ thấy rằng những  tiêu đề  có dấu ngoặc hiệu quả hơn không có khoảng 33%
Trong thực tế, chiến lược nhỏ này hiệu quả đến mức tôi thêm các dấu ngoặc trong hầu hết các tiêu đề của tôi

## Sử dụng các con số (Và không chỉ trên danh sách bài viết)
Các dữ liệu từ nhiều nguồn ( bao gồm BuzzSumo ) là tương đối rõ ràng: các con số sẽ cải thiện thông số CTR.
Vậy phần tuyệt nhất ở đây là gì?
Bạn có thể sự dụng các con số trong tiêu đề của bạn... thậm chi ngay cả khi nội dung không phải là danh sách bài viết.
Ví dụ, năm ngoái tôi đã đưa ra nghiên cứu này:
Như bạn có thể thấy, tôi đã thêm không chỉ 1, và 2 con số vào trong tiêu đề.

##  Rải đều các từ ngữ có ảnh hưởng vào trong các tag tiêu đề 
Những từ ngữ có ảnh hưởng là những cụm từ có những thể hiện cảm xúc 1 cách mạnh mẽ.
Bạn đoán đúng rồi đấy: việc sử dụng những từ ngữ mạnh sẽ giúp tiêu đề có bạn nổi bật và có nhiều click hơn.
Dưới đây là danh sách 1 vài từ ngữ mạnh mà tôi luôn ưa thích sử dụng    

Effective
Insane
That Will Case Study
Examples
Proven Study
New
Powerful

## Đừng quên tối ưu thẻ Description của bạn để cải thiện CTR
Đúng vậy các thể description không trực tiếp giúp cho việc sEO. Tôi đã nhận ra việc 1 thẻ description được tôi ưu có thể cải thiện CTR của bạn 1 cách ghê gớm.
ĐÂy là cách mà tôi tạo 1 tag description mà có kết quả:

###1 Đầu tiên hay làm cho nó có cảm xúc. 
Cũng giống như 1 tag tiêu đề, bạn muốn tag description của bạn có  1 chút cảm xúc trong đó.
Đây là 1 ví dụ.
###2 Tiếp đó, cho người ta biết lí do mà họ nên click vào kết quả của bạn?
Liệu kết quả của bạn có  sự bao quát không? Liệu nó dựa trên nghiên cứu chứ? đùa à? Hãy để điều đó trong mô tả của bạn
###3 Sau đó copy các từ và cụm từ và các quảng cáo trả phí ( AdWords) sử dụng.
Ví dụ khi tôi tìm "bone broth" tôi thấy những cụm từ này xuất hiện trong 2 bài quảng cáo
###4.Cuối cùng, thêm từ khóa đích của bạn.
Google sẽ bôi đậm nó, và khiến kết quả của bạn trở nên khác biệt.

## Chương 5: Làm thế nào để tối ưu nội dung nhằm cải thiện Tỷ lệ thoát và thời gian dừng

Ok, vậy là bạn đã sử dụng các mẹo cải thiện CTR của tôi. Và có nhiều người click vào kết quả của bạn hơn trước.
Giờ thì sao? Đúng rồi , bạn cần cho Google thấy rằng kết quả của bạn làm cho người dùng của họ hài lòng
Và cách tốt nhất đề làm điều này là gì? Cải thiện thời gian dừng của bạn

#### Google có thực sự sử dụng thời gian dừng không? Có đấy!
thời gian dừng là khoảng thời gian 1 người dùng tìm kiếm trên Goolge ở trên trang của bạn sau khi click vào kết quả tìm kiếm của bạn.
Rõ ràng là người dùng ở trên trang của bạn càng lâu càng tốt. Nó nói với Google rằng : "Man , mọi người đang yêu thích kết quả này. Hãy đẩy cho nó thêm ít điểm."
Và nếu có ai đó rời trang của bạn chỉ sau 2 giây, điều đó sẽ nói cho google "kết quả này thật tệ! Hãy hạ vài điểm của nó đi."
Vậy thật hợp lý khi RankBrain đo lường Dwell Time -  và trộn các kết quả xung quanh dựa trên tín hiệu này.
Trong thực tế, gần đây 1 kĩ sư Google đã nói rằng Google tin tưởng 100% với các dấu hiệu off-page( đặc biệt là các backlink). Thậm chí nếu Google vẫn sử dụng backlink, người kĩ sư này đã chỉ ra rằng:

"Google hiện nay đã tích hợp machine learning vào trong tiến trình ,  Vì vậy sau khi mô hình đào tạo khi một ai đó click vào trang và ở lại trang đó , Khi họ quay lại hoặc khi họ cố tìm một mối quan hệ thật sự nào đó"

Và dữ liệu sẽ dần tự cải thiện. Khi chúng tôi phân tích một tập hợp lớn các kết quả tìm kiếm của Google, chúng tôi đã tìm thấy mối tương quan giữa thứ hạng cao và tỷ lệ thoát thấp:

## Làm thế nào để giảm Bounce Rate và tăng Dwell Time
Giờ là lúc tôi sẽ chia sẻ 1 vài chiến lược đơn giản  mà bạn có thể dùng để tăng dwell time trên trang của bạn.

#### 1.Đẩy nội dung của bạn lên trên màn hình đầu tiên
Khi có ai đó click vào trang của bạn từ google, họ sẽ muốn có câu trả lời ngay lập tức.
Nói cách khác, họ không muốn lăn chuột xuống để đọc nội dung.
Đó là lý do tại sao tôi khuyên bạn nên xóa mọi thứ đẩy nội dung của bạn xuống dưới màn hình đầu tiên, như sau:
Thay vào đó, bạn muốn câu đầu tiên của nội dung và trung tâm nội dung của mình:
Bằng cách đó, bạn sẽ thu hút người đọc của bạn ngay lập tức

#### 2 Sử dụng giới thiệu ngắn (5-10 câu MAX)
Tin hay không thì tùy, nhưng tôi dành nhiều thời gian hơn cho phần giới thiệu của tôi hơn là tiêu đề của tôi.
Đó là bởi vì lời giới thiệu của bạn sẽ quyết định 90% khả năng người dùng quyết định ở lại hay là bỏ đi.
Và sau rất nhiều bài kiểm tra tôi đã nhận ra những câu giới thiệu ngắn có hiệu quả hơn.
Tại sao?
Khi có ai đó tìm kiếm gì đó trên Google, họ đã biết về chủ đề đó rồi. Vì vậy không cần phải giới thiệu quá dài dòng.
Thay vào đó, hãy sử dụng phần giới thiệu của bạn để bán nội dung mà họ sắp đọc, như sau:
Khi ai đó tìm kiếm từ khóa "white hat sEO" mà đọc được dòng giới thiệu này họ sẽ nghĩ "Ruyệt vời! Đây đúng là nơi tôi tìm"

#### 3 Xuất bản những nội dung dài, có chiều sâu
Tôi đã thử nghiệm điều này 10 cách khác nhau vào thứ ba. Và tôi có thể khẳng định với bạn rằng:
Nội dung dài = Dwell Time tốt hơn
Rõ ràng là việc đọc 1 bài hướng dẫn 2000 từ sẽ lâu hơn là 1 bài viết blog 400 từ. Nhưng đấy chỉ là 1 phần thôi.
Lí do khác mà khiến nội dung có cấu trúc dài sẽ làm tăng Dwell Time là nội dung dài có thể trả lời đầy đủ cho câu hỏi của người dùng
Ví dụ, bạn tìm kiểm "cách chạy marathon"
Và kết quả đầu tiên bạn click vào là 1 bài viết 300 từ. Nó như kiểu 1 câu trả lời ngắn gọn cho câu hỏi của bạn... nhưng bạn muốn nhiều hơn.
Vì vậy bạn click vào nút back để tìm thứ gì đó tốt hơn( và bạn còn nhớ không, Google gọi đây là Pogo sticking)
Và lần này bạn trúng số độc đắc.
Bạn tìm được 1 bài hướng dẫn  toàn diện và có mội thứ bạn cần biết về chạy 1 cuộc marathon.
Vì vậy bạn lấy 1 cốc cafe và đọc bài hướng dẫn từ đầu đến cuối. Bạn thậm chí còn đọc lại từng phần. Việc đọc thể này sẽ cải thiện đáng kể Dwell Time.
Các nội dung có trúc dài cũng rất hiệu quả khi tôi chỉ định xuất bản các bài viết có ít nhất 2000 từ.

#### 4 Chia nhỏ nội dung của bạn thành các khối có kích thước nhỏ
Sự thật là:
Đọc 2000 từ rất khó khăn.
Và thậm chí còn khó hơn khi 2000 từ đó được biểu diễn như là 1 bức tường chữ lớn vậy.
May mắn là, có 1 cách đơn giản để giải quyết vấn đề này: đó là các tiêu đề phụ.
Tiêu đề phụ - tiêu đề phụ sẽ chia nội dung của bạn thành các phần nhỏ mà vẫn có thể hiểu được. Điều này giúp tăng khả năng đọc, và tất nhiên là cả Dwell Time.
Tôi đã sử dụng rất nhiều tiêu đề phụ trong Backlink vì lí do cụ thể: đặc biệt, tôi cố gắng đưa 1 tiêu đề phụ vào với mỗi nội dung 200 từ.

Mẹo: Tránh các tiêu đề phụ nhàm chán như “Backhand Drills” hoặc “Stay Hydrated". Thay vào đó, hãy đóng gói các tiêu đề phụ của bạn bằng cảm xúc. Ví dụ: “3 Backhand Drills đơn giản sử dụng thuận lợi” và “Nghiên cứu mới nói về việc giữ Hydrated."

## chương  6:Tối ưu hóa thêm RankBrain. Chiến lược và nghiên cứu điển hình

Trong chương này, tôi sẽ giới thiệu một số chiến lược nhanh mà bạn có thể sử dụng để tối ưu hóa trang web của mình cho RankBrain.

###Tăng nhận thức về thương hiệu. Cải thiện CTR

Tôi đã chỉ cho bạn cách tính số, cảm xúc và từ năng lượng có thể cải thiện CTR không phải trả tiền của bạn.
Nhưng có 1 thứ khác tôi chưa đề cập : nhận diện thương hiệu.
Không cần phải nói, rõ ràng nếu ai đó biết về thương hiệu của bạn, họ sẽ thích click vào trang của bạn hơn trong các kết quả tìm kiếm. Thực tế dữ liệu từ WordStream chỉ ra rằng việc nhận diện thương hiệu có thể tăng CTR lên 342%.
Ví dụ, hay xem những kết quả tìm kiếm sau:
2 trang nào được click vào nhiều nhất? Rõ ràng là NYTimes.com và Simply Recipes rồi!
Nói cách khác, bạn muốn mọi người viết về thương hiệu của bạn trước khi tìm kiếm trên Google.
Làm cách nào để bạn tăng nhận diện thương hiệu của bạn?
#### 1 Đầu tiên hãy thử Facebook ads.
Thậm chi nếu người dùng không click và chuyển hướng, Facebook ads có thể đặt thương hiệu của bạn trước tầm mắt của rất nhiều người.
Và khi những con mắt đó lướt qua các kết qua tìm kiểm, họ sẽ thích click vào kết quả của bạn hơn.

#### 2 Ngoài ra, tạo một bản tin email có nhanh

Không có gì làm tăng nhận thức về thương hiệu hơn là gửi nội dung có giá trị đến hộp thư đến của mọi người.

Thực tế, tỷ lệ phát triển của tôi cao hơn mức trung bình của ngành bởi vì tôi chỉ gửi những thứ tốt:

Không cần phải nói, những người đăng ký của tôi đã học được rằng tài liệu của tôi là tốt nhất trong kinh doanh. Vì vậy, khi Backlinko xuất hiện trên trang 1, họ có nhiều khả năng nhấp vào kết quả của tôi hơn.

#### 3 Cuối cùng, hãy thực hiện “Nội dung Blitz”.
1 "Nội dung Blitz" là khi bạn xuất bản rất nhiều nội dung trong 1 khoảng thời gian ngắn. Và tin tôi đi: cách này hiệu quả hơn nhiều là việc ra bài viết cách nhau hàng năm trời.
Thực tế, tôi thường sử dụng Nội dung Blitz khi bắt đầu Backlinko.
Tôi đã xuất bản bài đăng của khách:
Tôi đã vào Podcasts:
Tôi thậm chí là đồng tác giả một hướng dẫn với Neil Patel:
(Tất cả trong một khoảng thời gian vài tháng)
Và điều này đã giúp Backlinko từ "Cái gì vậy?" Đến "Thật là một trang tuyệt vời!" Trong thời gian kỷ lục.

#### Chuyển từ “Zeros” thành “Heros”
Bạn có 1 trang trên trên site của bạn không tốt như bạn muốn không?
Tôi có 1 tin tốt đây: nếu bạn quay lại và tối ưu trang đó cho RankBrain, bạn có có thể tăng thứ hạng của nó 1 cách đáng kể.
Ví dụ, Sean từ Proven.com có 1 bài hướng dẫn chi tiết trên trang của anh ta về những thứ đang OK nhưng không được xếp hạng tốt như anh ấy kỳ vọng. Và Sean nhận ra rằng tag tiêu đề trang của anh ấy  không đủ huyết phục mọi người click vào:
Vì vậy anh ấy đã thêm 1 con số, 1 Power Word và dấu ngoặc đơn vào tag tiêu đề:
Và từng thay đổi đơn tăng lượng organic trafic của Sean trên trang của anh ý gần 128%.
Và, sự tăng traffic dựa trên 1 sự thật đơn giản là có càng nhiều người click vào kết quả của Sean.
Nhưng phần quan trọng nhất của câu chuyện là RankBrain sẽ chú ý đến lượng tăng CTR ... và cho trang của Sean thêm vào điểm xếp hạng:

#### Sử dụng từ khóa LSI để điền vào "Khoảng trống nội dung"
LSI Keywords là các từ và cụm từ liên quan đến chủ đề chính của nội dung.
Tại sao các LSI Keyword quan trọng? Vì chúng là điều kiện để RankBrain hoàn toàn hiểu được trang của bạn.
Ví dụ, giả sử bạn đang viết 1 bài hướng dẫn về việc xây dựng link.
LSI Keywords là những thứ như là:

Backlinks
Domain Authority
Email outreach
Anchor text

Và khi RankBrain thấy rằng nội dung của bạn có chưa những từ này, họ tin chắc rằng trang của bạn viết về xây dựng link...
có nghĩa là bạn gần như được xếp hạng cho những từ khóa liên quan đến chủ đề đó.

Bạn có thể tìm LSI keyword với Công cụ hiểu ngôn ngữ tự nhiên Watson.
Công cụ này nghiên cứu nội dụng bạn đưa ra với những khái niệm, thực thể và danh mục.
Ví dụ khi bạn điền phần đầu của bài hướng dẫn này, nó sẽ chỉ ra các khải niệm liên quan đến RankBrain.
Phần thú vị là tôi không hề đề cập quá nhiều đến những từ này trong bài hướng dẫn. Như RankBrain, Watson hiểu được nội dung của tôi viết về cái gì. Thật là tuyệt.
Và khi bạn thêm LSI keyword vào bài viết của bạn, bạn sẽ đảm bảo với RankBrain rằng nội dung của bạn rất chất lượng.
