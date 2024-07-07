### How to use Clash in Kali Linux (also useful in other Linux OS)

### 如何在 Kali Linux 中使用 Clash（同样适用于其他 Linux 操作系统）

#### Step 1: Install Clash

#### 第一步：安装 Clash

You should click [here](https://github.com/Dreamacro/clash/releases/download) to choose your ideal Clash version to download.
你应该点击[这里](https://github.com/Dreamacro/clash/releases/download)选择你需要的 Clash 版本进行下载。

I choose the clash-linux-amd64 version.
我选择的是 clash-linux-amd64 版本。

[]: Sadly, the link seems to be not found, you can search the resource on the web.
[]: 很遗憾，这个链接似乎找不到了，你可以在网上搜索资源。

#### Step 2: Unzip the file and set up

#### 第二步：解压文件并设置

After you get the resource, you should do the following:
在获取资源后，你应该进行以下操作：

```
1. Create a folder.
1. 创建一个文件夹。
   e.g., mkdir /usr/clash
   例如：mkdir /usr/clash

2. cd /usr/clash, put the .gz file and unzip it.
2. cd /usr/clash，把.gz文件放入并解压。

3. ./clash-linux-amd64
3. ./clash-linux-amd64
   If it does not work, use the command
   如果无法运行，使用命令
   chmod +x clash-linux-amd64
   to give it permission.
   给予权限。
```

#### Step 3: Get the right YAML

#### 第三步：获取正确的 YAML 文件

After running ./clash-linux-amd64, you can see a config.yaml file in the folder `/root/.config/clash`.
运行./clash-linux-amd64 后，你可以在文件夹 `/root/.config/clash` 中看到一个 config.yaml 文件。

You should visit a website to get and download your subscription file, e.g., `xxx.yaml`.
你应该访问一个网站获取并下载你的订阅文件，例如，`xxx.yaml`。

Then replace the original YAML file with your downloaded YAML file.
然后用你下载的 YAML 文件替换原始 YAML 文件。

#### Step 4: Proxy

#### 第四步：设置代理

You also need to set the proxy in the default browser, Firefox.
你还需要在默认浏览器 Firefox 中设置代理。

    1. Firefox Settings -> Network
    1. Firefox设置 -> 网络

    2. ./clash-linux-amd64
    2. ./clash-linux-amd64

3. Go to http://clash.razord.top/#/proxies to set and choose your ideal proxy node.
4. 进入http://clash.razord.top/#/proxies 设置并选择你的理想代理节点。

#### Step 5: Test & Success

#### 第五步：测试并成功

You will see:
你会看到：

![test1](image.png)
![test2](image-2.png)

This means you are successful.
这意味着你已经成功了。

Now test connecting to youtube.com:
现在测试连接 youtube.com：

![test youtube](image-3.png)

Success!
成功！
