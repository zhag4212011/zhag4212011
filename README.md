# cd /etc/sysconfig/network-scripts
# vi ifcfg-eth0
# 240E:F7:A020:203::8:1
 <th>名称</th>
    <th>网址</th>
    <th>快速复制</th>
  </tr>
  <tr>
    <td>TXT 格式直播源</td>
    <td><a href="https://live.zbds.top/tv/iptv6.txt">https://live.zbds.top/tv/iptv6.txt</a></td>
    <td><button class="button" onclick="copyToClipboard('https://live.zbds.top/tv/iptv6.txt')">快速复制</button></td>
  </tr>
  <tr>
    <td>M3U 格式直播源</td>
    <td><a href="https://live.zbds.top/tv/iptv6.m3u">https://live.zbds.top/tv/iptv6.m3u</a></td>
    <td><button class="button" onclick="copyToClipboard('https://live.zbds.top/tv/iptv6.m3u')">快速复制</button></td>
  </tr>
</table>
[...document.getElementsByTagName("pre")].forEach(item => {
        item.style.position = "relative";
        let copyButton = document.createElement("button")
        copyButton.style.cssText = 'border-radius: 4px;position:absolute;right:10px;top:10px;cursor: pointer'
        copyButton.innerHTML = "复制";
        copyButton.onclick = function () {
            let copyData = item.firstChild.innerText
            copyToClipboard(copyData)
            copyButton.innerHTML = "复制成功";
            setTimeout(function() {
                copyButton.innerHTML = "复制";
            }, 1000);
        }
        item.appendChild(copyButton)
});[...document.getElementsByTagName("pre")].forEach(item => {
        item.style.position = "relative";
        let copyButton = document.createElement("button")
        copyButton.style.cssText = 'border-radius: 4px;position:absolute;right:10px;top:10px;cursor: pointer'
        copyButton.innerHTML = "复制";
        copyButton.onclick = function () {
            let copyData = item.firstChild.innerText
            copyToClipboard(copyData)
            copyButton.innerHTML = "复制成功";
            setTimeout(function() {
                copyButton.innerHTML = "复制";
            }, 1000);
        }
        item.appendChild(copyButton)
});[...document.getElementsByTagName("pre")].forEach(item => {
        item.style.position = "relative";
        let copyButton = document.createElement("button")
        copyButton.style.cssText = 'border-radius: 4px;position:absolute;right:10px;top:10px;cursor: pointer'
        copyButton.innerHTML = "复制";
        copyButton.onclick = function () {
            let copyData = item.firstChild.innerText
            copyToClipboard(copyData)
            copyButton.innerHTML = "复制成功";
            setTimeout(function() {
                copyButton.innerHTML = "复制";
            }, 1000);
        }
        item.appendChild(copyButton)
});