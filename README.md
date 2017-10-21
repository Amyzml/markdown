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

！[图片](https://tse2-mm.cn.bing.net/th?id=OIP.6EB68rfa4SdDG8lcyfEFlADwEs&w=200&h=250&c=7&qlt=90&o=4&pid=1.7)