### 测试 
```java
    public class ArticleLableDao {

	public void add(int articeId, int id) {
		String sql = "insert into t_article_label (aid,lid) values(?,?)";
		Dbhelp.update(sql,articeId,id);
		
	}

	public void delByArticleId(int id) {
		
		String sql = "delete from t_article_label where aid = ?";
		Dbhelp.update(sql, id);
	}
```


![头像](http://www.githead.com/assets/downloads/git_desktop.gif)

请登录[Bing](https://www.bing.com/)查看


![qi](http://a3.qpic.cn/psb?/V12UM34U0WbQxL/90osI.iQslfAEmVgPvMRoGygtuM8TPseapDqQ*x8oB8!/b/dPIAAAAAAAAA&bo=UwNTA1MDUwMDCSw!&rf=viewer_4)

