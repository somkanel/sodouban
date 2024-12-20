# sodouban 🎬📚🎮

sodouban 是一个开源项目，旨在为博客作者提供统一的样式，帮助他们方便地展示单部作品。通过该项目，你可以轻松创建包含电影、书籍、电视剧、游戏等内容的卡片，并通过简单的配置展示作品的封面、评分、简介等信息。

## 特性 ✨

- **统一样式**：为不同类型的作品提供标准化展示样式，帮助你快速呈现内容。
- **简易使用**：通过 HTML 和 CSS 实现，无需额外的技术栈或工具支持。
- **灵活自定义**：你可以自由定制作品展示中的内容，包括评分、简介、封面图等。
- **响应式设计**：卡片样式支持在不同设备上良好的展示，适配手机、平板、桌面等平台。

## 使用方法 🚀

1. **引入样式** 🎨

   你可以将 sodouban 提供的样式文件直接引入到你的项目中，或者将样式代码复制到你的项目里。这样就能轻松地应用统一的卡片样式。

2. **生成作品卡片** 🖼️

   在页面中插入所需作品类型的卡片模板。无论是电影、书籍、电视剧、游戏还是其他类型，你都可以通过简单的配置展示封面图、评分、简介等内容。

3. **自定义内容** ✏️

   你可以根据具体的作品，修改卡片内容。例如，更新作品的标题、评分、简介、封面等信息，确保卡片符合你的展示需求。

## 示例 📝

本项目提供了多个类型的卡片模板示例，你可以根据项目需求选择合适的卡片样式进行展示。

- 电影卡片 🎥

<div style="
    display: flex;
    align-items: center;
    background-color: #fff;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
    padding: 16px;
    max-width: 700px;
    width: 100%;
    font-family: 'Arial', sans-serif;
    margin: 20px auto;
    position: relative;
">
    <div style="
        flex-shrink: 0;
        width: 120px;
        height: 180px; 
        border-radius: 8px;
        overflow: hidden;
        margin-right: 16px;
    ">
        <img 
            src="https://image11.m1905.cn/uploadfile/2024/1011/20241011032603291436.jpg" 
            alt="Anora 海报" 
            style="
                width: 100%; 
                height: 100%; 
                object-fit: cover;
            "
        >
    </div>
    <div style="flex: 1;">
        <div style="
            font-size: 20px; 
            font-weight: bold; 
            color: #333; 
            margin-bottom: 8px;
        ">
            阿诺拉 Anora (2024)
        </div>
        <div style="
            display: flex; 
            align-items: center; 
            margin-bottom: 12px;
        ">
            <div style="
                font-weight: 600; 
                font-size: 14px; 
                color: #333; 
                margin-right: 8px;
            ">
                个人评分:
            </div>
            <div style="color: #f39c12;">
                ⭐⭐⭐⭐☆
            </div> 
        </div>
        <div style="
            font-size: 14px; 
            color: #666; 
            line-height: 1.6;
        ">
            阿诺拉是布鲁克林的性工作者，她邂逅了一个商界寡头的儿子并在冲动之下嫁给了他，这让她以为自己像灰姑娘一样终于遇到自己的王子。然而当结婚消息传到了俄罗斯，男方父母来到纽约取消婚姻，破灭了的阿诺拉的童话。
        </div>
    </div>
    <a href="https://movie.douban.com/subject/36195543/" 
       target="_blank" 
       style="
           position: absolute; 
           top: 16px; 
           right: 16px; 
           background-color: #6c8b5f; 
           color: white; 
           font-size: 12px; 
           padding: 4px 8px; 
           border-radius: 4px; 
           text-transform: uppercase; 
           text-decoration: none;
       ">
        Movie >>>
    </a>
</div>


- 书籍卡片 📖
- 电视剧卡片 📺
- 游戏卡片 🎮

每种类型的卡片都可以根据实际情况进行灵活的修改和扩展，方便在博客中使用。

## 贡献 🛠️

我们欢迎任何形式的贡献！如果你发现 bug，或者有功能改进的建议，欢迎提交 Issues 或者 Pull Requests。你的参与将帮助项目不断完善，感谢你对开源社区的支持！

## License 📄

本项目采用 MIT License，详情请见 [LICENSE](LICENSE) 文件。
