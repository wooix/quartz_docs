## 서론: 짧지만 강력한 마무리

졸업식을 마친 후, 진정한 배움이 시작되는 경험을 하셨나요? 시스템 설계도 마찬가지입니다. 이 책의 마지막 장을 향하면서, 우리가 제시한 이론과 개념들은 시작일 뿐이라는 점을 강조하고 싶습니다.

**결론부터 말하면, 좋은 시스템을 설계하는 능력은 수년간의 지식 축적을 요구합니다.** 다행히 이를 가속화하는 한 가지 지름길이 있습니다. 바로 실제 기업들이 구축해낸 시스템 아키텍처를 깊이 있게 연구하는 것입니다. 아래에 정리한 학습 자료들은 그러한 지름길을 제시합니다.

우리는 단순히 링크 목록을 제공하는 것이 아닙니다. **공유된 설계 원칙과 근저에 깔린 기술 모두에 주의를 기울일 것**을 강력히 권장합니다. 각각의 기술이 어떤 문제를 해결하는지 이해하고, 그 설계 결정의 맥락을 파악하는 것—이것이 여러분의 지식 기반을 강화하고 설계 프로세스를 다듬는 가장 확실한 방법입니다.

---

## 1절: 실제 시스템 아키텍처 (Real-world Systems)

### 기업의 기술 선택을 살펴보다

다음은 여러 기업의 설계 원칙을 이해하는 데 도움이 될 학습 자료들입니다. 각 링크는 그 기업이 대규모 사용자를 지원하기 위해 어떤 기술과 아키텍처를 선택했는지를 보여줍니다.

### 주요 시스템 사례 (Real-world System Case Studies)

| 기업/시스템        | 주제                                            | 참고 자료                  |
| ------------- | --------------------------------------------- | ---------------------- |
| **Facebook**  | Timeline: 비정규화의 힘                             | https://goo.gl/FCNrbm  |
| **Facebook**  | Scale at Facebook                             | https://goo.gl/NGTdCs  |
| **Facebook**  | Building Timeline: 인생 스토리 확장                  | https://goo.gl/8p5wDV  |
| **Facebook**  | Erlang at Facebook (Facebook Chat)            | https://goo.gl/zSLHrj  |
| **Facebook**  | Facebook Chat                                 | https://goo.gl/qzSiWC  |
| **Facebook**  | Finding a Needle in Haystack: 사진 저장소          | https://goo.gl/edj4FL  |
| **Facebook**  | Serving Facebook Multifeed: 성능 최적화            | https://goo.gl/adFVMQ  |
| **Facebook**  | Scaling Memcache at Facebook                  | https://goo.gl/rZiAhX  |
| **Facebook**  | TAO: 소셜 그래프 분산 데이터 저장소                        | https://goo.gl/Tk1DyH  |
| **Amazon**    | Amazon Architecture                           | https://goo.gl/k4feoW  |
| **Amazon**    | Dynamo: 고가용성 Key-value 저장소                    | https://goo.gl/C7zxDL  |
| **Netflix**   | 360도 Netflix 스택                               | https://goo.gl/rYSDTz  |
| **Netflix**   | A/Bout Testing: 실험 플랫폼                        | https://goo.gl/agbA4K  |
| **Netflix**   | Recommendations: 별점을 넘어서 (Part 1)             | https://goo.gl/A4FkYi  |
| **Netflix**   | Recommendations: 별점을 넘어서 (Part 2)             | https://goo.gl/XNPMXm  |
| **Google**    | Google Architecture                           | https://goo.gl/dvkDiY  |
| **Google**    | The Google File System (Google Docs)          | https://goo.gl/xj5n9R  |
| **Google**    | Differential Synchronization (Google Docs)    | https://goo.gl/9zqG7x  |
| **YouTube**   | YouTube Architecture                          | https://goo.gl/mCPRUF  |
| **YouTube**   | Seattle Conference on Scalability             | https://goo.gl/dH3zYq  |
| **Google**    | Bigtable: 구조화된 데이터 분산 저장소                     | https://goo.gl/6NaZca  |
| **Instagram** | Instagram Architecture: 1,400만 사용자, 테라바이트 데이터 | https://goo.gl/s1VcW5  |
| **Twitter**   | 1억 5천만 활성 사용자 처리 아키텍처                         | https://goo.gl/EwvfRd  |
| **Twitter**   | Scaling Twitter: 10,000% 성능 향상                | https://goo.gl/nYGC1k  |
| **Twitter**   | Snowflake: 고규모 고유 ID 생성 서비스                   | https://goo.gl/GzVWYm  |
| **Twitter**   | Timelines at Scale                            | https://goo.gl/8KbqTy  |
| **Uber**      | 실시간 마켓플레이스 스케일링                               | https://goo.gl/kGZuVy  |
| **Pinterest** | Scaling Pinterest                             | https://goo.gl/KtmjW3  |
| **Pinterest** | Pinterest Architecture Update                 | https://goo.gl/w6rRsf  |
| **LinkedIn**  | A Brief History of Scaling LinkedIn           | https://goo.gl/8A1Pi8  |
| **Flickr**    | Flickr Architecture                           | https://goo.gl/dWtgYa  |
| **Dropbox**   | How We've Scaled Dropbox                      | https://goo.gl/NjBDtC  |
| **WhatsApp**  | Facebook가 190억 달러로 인수한 WhatsApp               | https://bit.ly/2AHJnFn |

---

## 2절: 기업 엔지니어링 블로그 (Company Engineering Blogs)

### 직무 면접을 준비하면서 꼭 해야 할 일

특정 기업과의 면접을 준비 중이라면, **그 기업의 엔지니어링 블로그를 꼭 읽을 것**을 강력히 권장합니다. 이를 통해 그 기업이 채택하고 구현한 기술과 시스템에 친숙해질 수 있습니다.

더 나아가, 엔지니어링 블로그는 특정 분야에 대한 매우 귀중한 통찰력을 제공합니다. 이를 정기적으로 읽는다면, 더 나은 엔지니어가 되는 데 큰 도움이 됩니다. 마치 의학 전문가가 최신 학술지를 구독하는 것처럼, 우리도 자신의 분야에서 실제 문제 해결 사례를 학습하는 것이 중요합니다.

### 대표 기업 및 스타트업 엔지니어링 블로그

| 기업 | 블로그 링크 |
|------|-----------|
| Airbnb | https://medium.com/airbnb-engineering |
| Amazon | https://developer.amazon.com/blogs |
| Asana | https://blog.asana.com/category/eng |
| Atlassian | https://developer.atlassian.com/blog |
| BitTorrent | http://engineering.bittorrent.com |
| Cloudera | https://blog.cloudera.com |
| Docker | https://blog.docker.com |
| Dropbox | https://blogs.dropbox.com/tech |
| eBay | http://www.ebaytechblog.com |
| Facebook | https://code.facebook.com/posts |
| GitHub | https://githubengineering.com |
| Google | https://developers.googleblog.com |
| Groupon | https://engineering.groupon.com |
| High Scalability | http://highscalability.com |
| Instacart | https://tech.instacart.com |
| Instagram | https://engineering.instagram.com |
| LinkedIn | https://engineering.linkedin.com/blog |
| Mixpanel | https://mixpanel.com/blog |
| Netflix | https://medium.com/netflix-techblog |
| Nextdoor | https://engblog.nextdoor.com |
| PayPal | https://www.paypal-engineering.com |
| Pinterest | https://engineering.pinterest.com |
| Quora | https://engineering.quora.com |
| Reddit | https://redditblog.com |
| Salesforce | https://developer.salesforce.com/blogs/engineering |
| Shopify | https://engineering.shopify.com |
| Slack | https://slack.engineering |
| SoundCloud | https://developers.soundcloud.com/blog |
| Spotify | https://labs.spotify.com |
| Stripe | https://stripe.com/blog/engineering |
| System Design Primer (GitHub) | https://github.com/donnemartin/system-design-primer |
| Twitter | https://blog.twitter.com/engineering/en_us.html |
| Thumbtack | https://www.thumbtack.com/engineering |
| Uber | http://eng.uber.com |
| Yahoo | https://yahooeng.tumblr.com |
| Yelp | https://engineeringblog.yelp.com |
| Zoom | https://medium.com/zoom-developer-blog |

---

## 에필로그: 축하합니다 (Afterword)

### 여정의 끝, 새 시작의 첫걸음

축하합니다! 여러분은 이 면접 가이드의 끝에 도달했습니다. 여러분은 시스템을 설계하기 위한 기술과 지식을 축적했습니다. 그리고 모든 사람이 여러분이 학습한 것을 학습할 만한 규율을 가지고 있지는 않다는 점을 기억하십시오. 잠시 멈추어 자신을 칭찬해주세요. **여러분의 노고는 반드시 결실을 맺을 것입니다.**

### 면접과 경력의 현실

꿈의 직장에 입사하는 것은 긴 여정이며, 시간과 노력이 많이 필요합니다. **연습이 완벽함을 만듭니다.** 최선을 다하시기 바랍니다!

### 마지막 인사

이 책을 구매하고 읽어주셔서 감사합니다. 여러분과 같은 독자들이 없었다면, 우리의 작업은 존재하지 않았을 것입니다. 이 책이 도움이 되었기를 바랍니다!

혹시 괜찮으시다면, Amazon에서 이 책을 리뷰해주시기 바랍니다: https://tinyurl.com/y7d3ltbc 이는 더 많은 훌륭한 독자분들을 끌어당기는 데 큰 도움이 될 것입니다.

새로운 장이 추가될 때 알림을 받고 싶으시다면, 다음 이메일 구독 링크에 등록해주세요: https://bit.ly/3dtIcsE

이 책에 대한 의견이나 질문이 있으시면, systemdesigninsider@gmail.com 으로 편하게 이메일을 보내주세요. 또한 오류를 발견하신다면 알려주셔서 다음 판에서 수정할 수 있도록 도와주세요. 감사합니다!

---

## 번역 노트

이 문서는 "System Design Interview: An Insider's Guide, 2nd Edition"의 Chapter 16을 한국어로 번역한 것입니다. 원문의 실용적이고 직설적인 어조를 유지하면서, 한국 독자들이 더욱 쉽게 이해할 수 있도록 번역되었습니다. 

특히 이 장은 지금까지 배운 개념들을 실제 기업의 사례를 통해 심화 학습할 수 있도록 돕는 자료 모음집입니다. 각 링크들은 Facebook, Google, Netflix, Amazon, Twitter 등 대규모 시스템을 운영하는 기업들이 공개한 설계 결정과 기술 검토 자료들로, 시스템 설계 면접 준비뿐만 아니라 평생 엔지니어링 학습의 귀중한 자산이 될 것입니다.
