# MiM Selective XRay — Ver1.2

選択した表面越しにオブジェクトを表示し、VRChatのExpressionsメニューでON/OFFを切り替えるPCアバター向けツールです。

## 導入

Unity 2022.3（Built-in Render Pipeline）、VRChat Avatars SDK、Modular Avatar、lilToonが必要です。

1. 必要なパッケージとSelective XRayをUnityへインポートします。
2. **MiM → Selective XRay** を開きます。
3. アバター・貫通対象・透過対象を指定し、必要に応じて内部の表示対象を追加します。
4. 初期状態と状態記憶を設定して、**複製してON/OFFメニューを作成**を押します。
5. シーンを保存します。使い方の詳細はツールの**使い方**ボタンから確認できます。

## 更新履歴

### Ver1.2（2026-10-24）

- マテリアルバリアントを独立した複製に変換し、XRayシェーダーへの変更に失敗する問題を修正しました。
- 貫通対象の通常の半透明lilToonマテリアルに対応しました。
- 既存の設定へ適用するには、使い方に従って旧設定を取り外し、Ver1.2で作り直してください。

### Ver1.1（2026-10-20）

- 半透明の透過対象と不透明部分の描画順を分け、半透明の髪などの後ろが正しく表示されない問題を修正しました。
- 既存の設定には、使い方に従って設定を作り直すことで修正が適用されます。

## 更新

ツールは起動時に更新情報を確認します。新しいバージョンがある場合はバージョンと変更内容を表示します。自動インストールは行いません。

## 対応条件

PC版アバター向けです。貫通対象はlilToonの不透明・通常の半透明マテリアルに対応します。屈折や特殊な透明モードは対象外です。Quest/Android、URP/HDRP、複数の貫通範囲を重ねる構成には対応していません。

## お問い合わせ

[MiM Discord](https://discord.gg/cpu6ZFRJE)へ、バージョン・再現手順・エラーメッセージを添えてお問い合わせください。

---

Selective XRay provides selective see-through rendering and a VRChat ON/OFF menu setup tool for PC avatars. Requires Unity 2022.3 Built-in RP, VRChat Avatars SDK, Modular Avatar and lilToon. Open **MiM → Selective XRay** and use **How to** for instructions.

[BOOTHの商品ページ](https://howareyu.booth.pm/items/9011263)