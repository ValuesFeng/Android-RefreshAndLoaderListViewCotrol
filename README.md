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
