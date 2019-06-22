# 代码修改注意事项

多余页面已删除

所有页面头部参考index.html文件的头部导航，不然有很多空白页面无法点进

修改时可以用Google浏览器翻译整个网页，将英文改成中文

使用开发者工具选中图片到相应位置替换空白图片

翻译文字时可参考网页：[效果展示](https://easetemplate.com/free-website-templates/travelair/index.html)

把所有页面导航栏中的
```
 <!-- navigations-->
                            <div class="navigation">
                                <div id="navigation">
                                    <ul>
                                        <li class="active"><a href="index.html">Home</a></li>
                                        <li class="has-sub"><a href="#">Tour Packages</a>
                                            <ul>
                                                <li><a href="tour-list.html">Tour List</a></li>
                                                <li><a href="tour-single.html">Tour Single</a></li>
                                                <li><a href="tour-single-list.html">Tour List Single </a></li>
                                            </ul>
                                        </li>
                                        <li><a href="about.html">About</a></li>
                                        <li class="has-sub"><a href="#">Blog</a>
                                            <ul>
                                                <li><a href="blog-default.html">Blog Default</a></li>
                                                <li><a href="blog-single.html">Blog Single</a></li>
                                            </ul>
                                        </li>
                                        <li class="has-sub"><a href="#">Pages</a>
                                            <ul>
                                                <li><a href="testimonials.html">Clients Reviews</a> </li>
                                                <li><a href="tour-booking.html">Tour Booking</a> </li>
                                                <li><a href="tab.html">Tabs</a> </li>
                                                <li><a href="alerts.html">Alerts</a> </li>
                                                <li><a href="accordions.html">Accordions</a> </li>
                                                <li><a href="gallery.html">Gallery</a> </li>
                                                <li><a href="404-page.html">404 page</a> </li>
                                                <li><a href="call-to-action.html">Call To Actions</a></li>
                                                <li><a href="styleguide.html">styleguide</a> </li>
                                            </ul>
                                        </li>
                                        <li><a href="contact-us.html">Contact</a></li>
                                        <li><a href="template-feature.html">Template Feature</a></li>
                                    </ul>
                                </div>
                            </div>
                            <!-- /.navigations-->
```
改为：

```
  <div class="navigation">
                                <div id="navigation">
                                    <ul>
                                        <li class="active"><a href="index.html">主页</a></li>
                                        <li class="has-sub"><a href="#">旅行套餐</a>
                                            <ul>
                                                <li><a href="tour-list.html">旅行清单</a></li>
                                                <li><a href="tour-single.html">单人游</a></li>
                                                <li><a href="tour-single-list.html">单人游套餐 </a></li>
                                            </ul>
                                        </li>
                                        <li><a href="about.html">关于</a></li>
                                        <li class="has-sub"><a href="#">页面</a>
                                            <ul>
                                                <li><a href="testimonials.html">客户评论</a> </li>
                                                <li><a href="tour-booking.html">行程预订</a> </li>
                                                <li><a href="gallery.html">画廊</a> </li>
                                                <li><a href="accordions.html">帮助</a> </li>
                                                <li><a href="call-to-action.html">优惠活动</a></li>
                                            </ul>
                                        </li>
                                        <li><a href="contact-us.html">联系我们</a></li>
                                    </ul>
                                </div>
```

报告书可介绍特点

bookstrap框架

video.js视频播放
