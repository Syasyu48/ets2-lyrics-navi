# ETS2 Lyrics HUD

## 日本語

ETS2 Lyrics HUD は、Euro Truck Simulator 2 の TruckersMP 向けに開発中の非公式 Windows アドオンです。[TruckersMP Game Client SDK](https://github.com/TruckersMP/GameClientSDK) を使い、ゲーム画面に歌詞を重ねて表示します。Spotify で再生中の曲と再生位置に合わせて、対応する歌詞をアニメーション付きで表示することを目指しています。

現在は TruckersMP 上でデモ歌詞の表示と、`Ctrl+Shift+F8` による表示切り替えを確認済みです。Spotify の実曲と歌詞を使った通しテストはこれからです。

### 歌詞データの取り扱い

歌詞はアプリ内での表示に使い、API レスポンスの再配布は行いません。歌詞とともに、レスポンスごとの提供元を表示します。`spicy_lyrics` のレスポンスでは投稿者と、記載がある場合は制作者を、それぞれのリンク付きで表示します。レスポンスの一時キャッシュはメモリ上で最大5分です。歌詞の利用に必要な権利者の許諾は別途確認します。[Spicy Lyrics API 利用規約](https://developers.spicylyrics.org/terms) · [プライバシーポリシー](https://developers.spicylyrics.org/privacy)

## English

ETS2 Lyrics HUD is an independent Windows add-on in development for Euro Truck Simulator 2 on TruckersMP. It uses the [TruckersMP Game Client SDK](https://github.com/TruckersMP/GameClientSDK) to draw an in-game overlay. The goal is to display animated lyrics synced to the track and playback position in Spotify.

The sample display and its `Ctrl+Shift+F8` toggle have been tested in TruckersMP. End-to-end testing with live Spotify playback and lyrics is pending.

### Lyrics data handling

Lyrics are displayed within the app. API responses are never redistributed. Each response supplies its own attribution, which is shown with the lyrics. For `spicy_lyrics` responses, the uploader and the maker, when provided, are credited and linked. Responses may be cached in memory for up to five minutes. Permission to use song lyrics is handled separately with the relevant rights holders. [Spicy Lyrics API Terms of Service](https://developers.spicylyrics.org/terms) · [Privacy Policy](https://developers.spicylyrics.org/privacy)
