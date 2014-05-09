Android-RefreshAndLoaderListViewCotrol
======================================
- 下拉刷新
 + 1.是否刷新
    listView.setCanRefresh(!listView.isCanRefresh());
 + 2.刷新添加音效（正在修改）
 + 3.刷新后是否显示第一条的item
    listView.setMoveToFirstItemAfterRefresh(!listView.isMoveToFirstItemAfterRefresh());
- 加载更多
 + 1.是否可以加载更多
    listView.setCanLoadMore(!listView.isCanLoadMore());
 + 2.是否自动加载更多
    listView.setAutoLoadMore(!listView.isAutoLoadMore());


下拉刷新：
![下拉刷新](http://1.valuesgithubimages.sinaapp.com/images/1.png)




松开刷新：
![松开刷新](http://1.valuesgithubimages.sinaapp.com/images/2.png)



刷新中：
![刷新中](http://1.valuesgithubimages.sinaapp.com/images/3.png)



加载更多：
![加载更多](http://1.valuesgithubimages.sinaapp.com/images/4.png)


加载中：
![加载中](http://1.valuesgithubimages.sinaapp.com/images/5.png)
