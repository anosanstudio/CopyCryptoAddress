# CopyCryptoAddress
A html file allows you to copy address

## 使用方法

把html檔下載到電腦裡後，用記事本打開，找到程式碼
```
    <div>錢包名稱</div>
    <span id="a1">123abc...xyz987</span>
    <div class="tooltip">
      <button id="btn1" class="btn">
        <span class="tooltiptext" id="toolText1">Copy address</span>
        Copy
      </button>
    </div><br />

```
可以把```錢包名稱```改成自己錢包的名稱，```123abc...xyz987```改成要複製的地址，修改完後存檔，用瀏覽器打開，按地址旁的Copy，就可以把地址複製到剪貼簿裡

裡面原本預設兩個錢包，如果想要增加更多錢包位置可以把下面這段複製起來
```
    <div>ETH錢包</div>
    <span id="a2">0xdef...abc123</span>
    <div class="tooltip">
      <button id="btn2" class="btn">
        <span class="tooltiptext" id="toolText2">Copy address</span>
        Copy
      </button>
    </div><br />
```
並且貼在這段下面，除了更改```ETH錢包```與```0xdef...abc123```成需要的錢包名稱與地址外

還需要將```<span id="a2">```中的```a2```改成```a3```，```<button id="btn2" class="btn">```中的```btn2```改成```btn3```

```<span class="tooltiptext" id="toolText2">```中的```toolText2```改成```toolText3```

存檔後就可以看到多一個錢包可以複製，如果要數量更多的錢包可以用一樣的方法增加，只是數字要再加1
