# TVBoxOSC
真的没有QQ群、QQ频道、论坛。打包分发注意开源协议，保留出处，不守规矩就不要搞。
TVBox GitHub社区 根据官方代码仓生成的安卓应用。
____________
=== Source Code - Editing the app default settings === /src/main/java/com/github/tvbox/osc/base/App.java

```
private void initParams() {

    putDefault(HawkConfig.HOME_REC, 2);       // Home Rec 0=豆瓣, 1=推荐, 2=历史
    putDefault(HawkConfig.PLAY_TYPE, 1);      // Player   0=系统, 1=IJK, 2=Exo
    putDefault(HawkConfig.IJK_CODEC, "硬解码");// IJK Render 软解码, 硬解码
    putDefault(HawkConfig.HOME_SHOW_SOURCE, true);  // true=Show, false=Not show
    putDefault(HawkConfig.HOME_NUM, 2);       // History Number
    putDefault(HawkConfig.DOH_URL, 2);        // DNS
    putDefault(HawkConfig.SEARCH_VIEW, 2);    // Text or Picture

}
```
