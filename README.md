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
请登录[Bing](https://www.bing.com/)查看

！[图片](https://cn.bing.com/images/search?q=%e5%88%98%e4%ba%a6%e8%8f%b2%e5%86%99%e7%9c%9f&FORM=R5FD0)