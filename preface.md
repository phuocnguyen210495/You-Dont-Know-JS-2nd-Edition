# Bạn chưa biết JS - Phiên bản thứ 2
# Lời nói đầu

Chào mừng bạn đến với ấn bản thứ 2 của bộ sách *You Don't Know JS* (**YDKJS**) được hoan nghênh rộng rãi: *You Don't Know JS **Yet*** (**YDKJSY**).

Nếu bạn đã đọc bất kỳ cuốn sách xuất bản đầu tiên nào, bạn có thể mong đợi một cách tiếp cận được làm mới trong những cuốn mới này, với nhiều thông tin cập nhật về những gì đã thay đổi trong JS trong năm năm qua. Nhưng điều tôi hy vọng và tin rằng bạn vẫn sẽ nhận được là cam kết tôn trọng JS và đào sâu vào điều gì thực sự khiến nó trở nên đáng chú ý.

Nếu đây là lần đầu tiên bạn đọc những cuốn sách này, tôi rất vui vì bạn đã ở đây. Chuẩn bị cho một cuộc hành trình sâu và rộng vào tất cả các góc của JavaScript.

Nếu bạn chưa quen với lập trình hoặc JS, hãy lưu ý rằng những cuốn sách này không phải là một "phần giới thiệu về JavaScript" nhẹ nhàng. Tài liệu này, đôi khi, phức tạp và đầy thách thức, và đi sâu hơn nhiều so với tài liệu điển hình cho người học lần đầu. Bạn được chào đón ở đây bất kể kiến ​​thức của bạn là gì, nhưng những cuốn sách này được viết với giả định bạn đã hiểu rõ về JS và có ít nhất 6–9 tháng kinh nghiệm với nó.

## Các bộ phận

Những cuốn sách này tiếp cận JavaScript có chủ ý ngược lại với cách xử lý ngôn ngữ *The Good Parts*. Không, điều đó không có nghĩa là chúng tôi đang xem xét *the bad parts*,nhưng đúng hơn là khám phá **all the parts**.

Có thể bạn đã được cho biết hoặc tự cảm thấy rằng JS là một ngôn ngữ có sai sót sâu sắc, được thiết kế kém và triển khai không nhất quán. Nhiều người đã khẳng định rằng đó là ngôn ngữ phổ biến nhất trên thế giới; rằng không ai viết JS bởi vì họ muốn, chỉ vì họ phải dành vị trí của nó ở trung tâm của web. Đó là một tuyên bố vô lý, không lành mạnh và hoàn toàn hạ mình.

Hàng triệu nhà phát triển viết JavaScript mỗi ngày và nhiều người trong số họ đánh giá cao và tôn trọng ngôn ngữ này.

Giống như bất kỳ ngôn ngữ tuyệt vời nào, nó có những phần rực rỡ cũng như những vết sẹo của nó. Ngay cả bản thân người tạo ra JavaScript, Brendan Eich, cũng than thở một số phần đó là sai lầm. Nhưng anh ấy đã sai: họ không hề sai lầm. JS là như ngày nay — ngôn ngữ lập trình phổ biến nhất trên thế giới và do đó có ảnh hưởng nhất — chính vì *all those parts*.

Đừng mua những thứ dối trá mà bạn chỉ nên tìm hiểu và sử dụng một bộ sưu tập nhỏ các bộ phận tốt trong khi tránh tất cả những thứ xấu. Đừng mua dầu rắn "X là Y mới", vì một số tính năng mới của ngôn ngữ ngay lập tức khiến mọi cách sử dụng của một tính năng trước đó trở nên lỗi thời và thiếu hiểu biết. Đừng nghe khi ai đó nói rằng mã của bạn không "hiện đại" bởi vì nó chưa sử dụng tính năng stage-0 mới chỉ được đề xuất vài tuần trước!

Mọi phần của JS đều hữu ích. Một số bộ phận hữu ích hơn những bộ phận khác. Một số phần yêu cầu bạn phải cẩn thận và chủ ý hơn.

Tôi thấy thật vô lý khi cố gắng trở thành một nhà phát triển JavaScript thực sự hiệu quả trong khi chỉ sử dụng một phần nhỏ những gì ngôn ngữ này cung cấp. Bạn có thể tưởng tượng một công nhân xây dựng với một hộp công cụ đầy ắp công cụ, người chỉ sử dụng búa và chế giễu chiếc tuốc nơ vít hoặc thước dây là người kém cỏi? Điều đó thật ngớ ngẩn.

Tuyên bố chưa được bảo lưu của tôi là bạn nên học tất cả các phần của JavaScript và sử dụng chúng khi thích hợp! Và nếu tôi có thể mạnh dạn đề xuất: đã đến lúc loại bỏ bất kỳ cuốn sách JS nào cho bạn biết cách khác.

## Tiêu đề?

Vậy tiêu đề của bộ truyện là gì?

Tôi không cố gắng xúc phạm bạn với những lời chỉ trích về sự thiếu kiến ​​thức hoặc hiểu biết hiện tại của bạn về JavaScript. Tôi không khuyên bạn không thể hoặc sẽ không thể học JavaScript. Tôi không khoe khoang về trí tuệ nội gián tiên tiến bí mật mà tôi và chỉ một số ít người được chọn sở hữu.

Nghiêm túc mà nói, tất cả những điều đó đều là phản ứng thực sự với tiêu đề bộ truyện gốc trước khi mọi người thậm chí đọc sách. Và chúng vô căn cứ.

Điểm chính của tiêu đề "Bạn chưa biết JS" là chỉ ra rằng hầu hết các nhà phát triển JS không dành thời gian để thực sự hiểu mã mà họ viết hoạt động như thế nào. Họ biết rằng nó hoạt động - rằng nó tạo ra một kết quả mong muốn. Nhưng họ hoặc không hiểu chính xác bằng cách nào, hoặc tệ hơn, họ có một mô hình tinh thần không chính xác về cách mà chúng chùn bước khi xem xét kỹ hơn.

Tôi đang đưa ra một thử thách nhẹ nhàng nhưng nghiêm túc cho bạn đọc, đó là gạt bỏ những giả định bạn có về JS, và tiếp cận nó với đôi mắt mới mẻ và sự tò mò được khơi dậy khiến bạn phải hỏi tại sao cho mỗi dòng mã bạn viết. Tại sao nó làm những gì nó làm? Tại sao một cách tốt hơn hoặc thích hợp hơn một nửa cách khác mà bạn có thể đã thực hiện được? Tại sao tất cả "những đứa trẻ nổi tiếng" đều nói làm X với mã của bạn, nhưng hóa ra Y có thể là lựa chọn tốt hơn?

Tôi đã thêm "Yet" vào tiêu đề, không chỉ vì đây là lần xuất bản thứ hai, mà bởi vì cuối cùng tôi muốn những cuốn sách này thách thức bạn một cách đầy hy vọng hơn là nản lòng.

Nhưng hãy để tôi nói rõ: Tôi không nghĩ rằng có thể biết hoàn toàn về JS. Đó không phải là thành tích cần đạt được mà là mục tiêu phấn đấu sau này. Bạn không biết hết mọi thứ về JS, bạn chỉ tiếp tục học ngày càng nhiều hơn khi bạn dành nhiều thời gian hơn cho ngôn ngữ này. Và càng đi sâu, bạn càng xem lại những gì bạn đã biết trước đây và bạn học lại từ người cũ đó

Tôi khuyến khích bạn áp dụng tư duy xung quanh JavaScript và thực sự là tất cả phát triển phần mềm, rằng bạn sẽ không bao giờ hoàn toàn thành thạo nó, nhưng bạn có thể và nên tiếp tục làm việc để tiến gần hơn đến kết thúc đó, một hành trình sẽ kéo dài toàn bộ sự nghiệp phát triển phần mềm của bạn và hơn thế nữa.

Bạn luôn có thể biết JS tốt hơn bạn hiện tại. Đó là những gì tôi hy vọng những cuốn sách YDKJSY này đại diện.

## Nhiệm vụ

Trường hợp này không thực sự cần thiết vì lý do tại sao các nhà phát triển nên coi trọng JS - tôi nghĩ rằng nó đã được chứng minh là xứng đáng hơn với vị thế hạng nhất trong số các ngôn ngữ lập trình trên thế giới.

Nhưng một trường hợp khác, quan trọng hơn vẫn cần được thực hiện, và những cuốn sách này đã vươn lên thách thức đó.

Tôi đã dạy hơn 5.000 nhà phát triển từ các nhóm và công ty trên khắp thế giới, tại hơn 25 quốc gia trên sáu lục địa. Và những gì tôi đã thấy là quá thường xuyên, những gì *đếm* nói chung chỉ là kết quả của chương trình, không phải cách chương trình được viết hoặc cách / tại sao nó hoạt động.

Kinh nghiệm của tôi không chỉ với tư cách là một nhà phát triển mà còn trong việc giảng dạy cho nhiều nhà phát triển khác cho tôi biết: bạn sẽ luôn hiệu quả hơn trong công việc phát triển của mình nếu bạn hoàn toàn hiểu cách mã của mình hoạt động hơn là bạn chỉ *chỉ* nhận nó để tạo ra kết quả mong muốn.

Nói cách khác, *đủ tốt để làm việc* thì không, và không nên, *đủ tốt*.

Tất cả các nhà phát triển thường xuyên phải vật lộn với một số đoạn mã không hoạt động chính xác và họ không thể tìm ra lý do. Nhưng quá thường xuyên, các nhà phát triển JS sẽ đổ lỗi cho điều này do ngôn ngữ này thay vì thừa nhận rằng sự hiểu biết của chính họ đang bị thiếu hụt. Những cuốn sách này đóng vai trò là cả câu hỏi và câu trả lời: tại sao nó lại làm * cái này * và đây là cách để nó làm *cái đó* thay thế.

Nhiệm vụ của tôi với YDKJSY là trao quyền cho mọi nhà phát triển JS đơn lẻ để sở hữu hoàn toàn mã họ viết, hiểu nó và viết có chủ đích và rõ ràng.

## Con đường

Một số bạn đã bắt đầu đọc cuốn sách này với mục tiêu hoàn thành tất cả sáu cuốn, liên tục.

Tôi xin lưu ý bạn nên cân nhắc thay đổi kế hoạch đó.

Tôi không có ý định đọc thẳng YDKJSY. Tài liệu trong những cuốn sách này dày đặc, bởi vì JavaScript mạnh mẽ, phức tạp và có nhiều phần khá phức tạp. Không ai có thể thực sự hy vọng *tải xuống* tất cả thông tin này vào bộ não của họ chỉ trong một lần chuyển và giữ lại bất kỳ lượng đáng kể nào của nó. Điều đó thật phi lý, và thật ngu ngốc khi thử.

Đề nghị của tôi là bạn dành thời gian của bạn để xem qua YDKJSY. Lấy một chương, đọc hết từ đầu đến cuối, sau đó quay lại và đọc lại từng phần. Dừng lại giữa mỗi phần và thực hành mã hoặc ý tưởng từ phần đó. Đối với các khái niệm lớn hơn, có lẽ là một ý kiến ​​hay nếu bạn dành vài ngày để đọc lại, đọc lại, thực hành, sau đó tiêu hóa thêm một số khái niệm nữa.

Bạn có thể dành một hoặc hai tuần cho mỗi chương, và một hoặc hai tháng cho mỗi cuốn sách và một năm hoặc hơn cho cả bộ truyện, và bạn vẫn sẽ không vắt kiệt từng chút YDKJSY.

Đừng say mê những cuốn sách này; hãy kiên nhẫn và trải rộng bài đọc của bạn. Hãy xen kẽ việc đọc với nhiều thực hành về mã thực trong công việc của bạn hoặc trong các dự án mà bạn tham gia. Vật lộn với những ý kiến ​​tôi đã trình bày trong suốt quá trình, tranh luận với những người khác và hơn hết, không đồng ý với tôi! Điều hành một nhóm học tập hoặc câu lạc bộ sách. Dạy các hội thảo nhỏ tại văn phòng của bạn. Viết các bài đăng trên blog về những gì bạn đã học được. Nói về những chủ đề này tại các buổi gặp mặt JS địa phương.

Mục tiêu của tôi không bao giờ là thuyết phục bạn đồng ý với ý kiến ​​của tôi, mà là khuyến khích bạn làm chủ và có thể bảo vệ ý kiến ​​của mình. Bạn không thể đến * ở đó * với việc đọc hết những cuốn sách này. Đó là điều mà cần một thời gian dài để xuất hiện, từng chút một, khi bạn nghiên cứu, suy ngẫm và tham quan lại.

Những cuốn sách này nhằm mục đích hướng dẫn thực địa về hành trình của bạn thông qua JavaScript, từ bất cứ nơi nào bạn đang ở với ngôn ngữ này, đến nơi hiểu biết sâu sắc hơn. Và bạn càng hiểu sâu về JS, bạn sẽ càng đặt ra nhiều câu hỏi và càng phải khám phá nhiều hơn! Đó là điều tôi thấy rất thú vị!

Tôi rất vui vì bạn đã bắt tay vào hành trình này, và tôi rất vinh dự khi bạn sẽ xem xét và tham khảo những cuốn sách này trong suốt chặng đường. Đã đến lúc bắt đầu *làm quen với JS*.
