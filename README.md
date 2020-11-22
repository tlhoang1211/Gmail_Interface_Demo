# Gmail_Interface_Demo

1. WindowActionModeOverlay in styles.xml is added to overlap the ActionMode onto Toolbar.

2. Research Retrofit 
https://topdev.vn/blog/retrofit-trong-android/
https://viblo.asia/p/huong-dan-su-dung-thu-vien-retrofit-de-call-api-voi-android-yMnKMmpgK7P

//model - đ giải thích đâu nhé :))

//network directory
3. ApiClient.java - This class creates the static retrofit instance.

4. ApiInterface.java - This class contains the rest api endpoints and the type of response it is expecting. In our case we have only one endpoint i.e inbox.json

//helper 
5. CircleTransform.java - This class is used to display the thumbnail image in circular shape using the Glide library.

6. DividerItemDecoration.java - This helps in adding divider lines in recycler view.

7. Flip Animation - t làm thêm không cần hiểu thích thì tự đọc nhé

------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Mấy cái rendering cũng thế. 
- Layouts thì t chia nhỏ ra xong lồng vào nhau thui (2 folder menu với layout)
