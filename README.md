# recommendation_system

## 一、《推荐系统实战》项亮编著

- 信息过载解决方法：
  - 雅虎：分类目录。互联网规模的扩大，覆盖面变小，越来越不能满足用户的需求
  - 谷歌：搜索引擎。需要用户主动提供准确的关键字
   
- 推荐：
  - 社会化推荐：别人的推荐
  - 基于内容的推荐：标签
  - 基于协同过滤的推荐：相同兴趣的用户的推荐

- 推荐算法的本质是通过一定的方式将用户和物品联系起来。

- 个性化推荐系统
  - 与搜索引擎不同，个性化推荐系统需要依赖用户的行为数据
  - 通过分析大量用户行为日志，给不同用户提供不同的个性化页面显示，来提高网站的点击率和转化率

- 个性化推荐的成功需要两个条件
  - 存在信息过载，因为如果用户可以很容易地从所有物品中找到信息的物品，就不需要个性化推荐了
  - 用户大部分时候没有特别明确的需求，因为如果用户有明确的需求，可以直接通过搜索引擎找到感兴趣的物品
  
  
### 个性化推荐系统的应用

- 电子商务 亚马逊
  - 个性化商品推荐列表
      - 推荐结果的标题、缩略图以及其它内容属性：告诉用户推荐内容的简要信息
      - 推荐结果的平均分：反映了推荐结果的总体质量，也代表了大部分用户对推荐内容的看法
      - 推荐理由：根据用户的历史行为给用户做推荐
      - 推荐结果反馈：加入购物车、收藏、评分、不感兴趣
      - 方式：
          - **基于物品的推荐**：推荐用户之前喜欢的物品相似的物品
          - **基于社交的推荐**：按照用户在facebook的好友关系，给用户推荐他们的好友喜欢的物品
  
  - 相关推荐列表
      - 购买了这个商品的用户也经常购买的其它商品
      - 浏览了这个商品的用户经常购买的其它商品
      - 使用不同用户行为计算物品的相关性
      - 打包销售，提供折扣
    
- 电影和视频网站 Netflix
  - 电影的标题和海报
  - 用户反馈模块：播放、评分和不感兴趣
  - 推荐理由：因为用户喜欢看过某部电影
  
  
- 个性化音乐网络电台 pandora、豆瓣、网易云音乐
  - pandora
      - 推荐算法主要来自于一个叫做音乐基因工程的项目，基于内容，其音乐家和研究人员亲自听了上万首来自不同歌手的歌，然后对歌曲的不同特性（比如旋律、节奏、编曲和歌词等）进行标注，这些标注被称为音乐的基因。
      - pandora根据专家标注的基因计算歌曲的相似度，并给用户推荐和他之前喜欢的音乐在基因上相似的其它音乐
  
  - Last.fm
      - 记录了所有用户的挺饿记录以及用户对歌曲的反馈，在这一基础上计算出不同用户在歌曲上的喜好相似度，从而给用户推荐和他有相似听歌爱好的其它用户喜欢的歌曲
      - 建立社交网络，让用户能够和其它用户建立联系，同时也能让用户给好友推荐自己喜欢的歌曲
      - 主要利用用户行为计算歌曲的相似度  
  
  - 音乐推荐的特点：
      - 物品空间大
      
      - 消费每首歌的代价很小：对于在线音乐来说，音乐都是免费的
      
      - 物品种类丰富：音乐种类丰富，流派很多
      
      - 听一首歌耗时很少
      
      - 物品重用率很高
      
      - 用户充满激情：一个用户会听很多首歌
      
      - 上下文相关：用户的口味很受当时心情和环境的影响
      
      - 次序很重要
      
      - 很多播放列表
      
      - 不需要用户全神贯注
      
      - 高度社会化
   
  
  
  
  
  
  
  
  
  
  
