## 1. 新規プロジェクト作成

1. `File`→`Save World As…`を選択する
2. ファイル名を`my_robot01.wbt`として保存
3. 中央左にある`RectangleArena`→`Add New`を選択
4. そのまま`Import`を選択
5. `C:\my_project\worlds\TinkerbotsBase.wbo`を開く
6. 画面中央左に`TinkerbotsBase`があり、かつ画面中央にロボットが表示されていることを確認し、上書き保存する



## 2. コントローラ・プログラムの作成

1. `Wizards`→`New Robot Controller`を選択
2. `New controller creation`ではそのまま次へ
3. `Language selection`では`C`を選択し次へ
4. `IDE selection`では`Webots (gcc / Makefile)`を選択し、次へ
5. コントローラー名を入力し、次へ
6. `Condusion`では`Open (コントローラー名) in Text Editor.`にチェックを入れ終了する
7. Webotsにて出てきたテンプレートのプログラムを削除する
8. `C:\my_project`にある`header_generator.bat`をコピーし、`controllers`ファイルを開く
9. 新しく作成したプログラムのフォルダを開き、`8.`にてコピーした`header_generator.bat`を張りつける
10. `header_generator.bat`をダブルクリックし、`tinkerbots_utility.c`と`tinkerbots_utility.h`が作成されたことを確認する
11. `C:\my_project\template.c`をメモ帳で開き、中身のコードをWebotsの画面中央右に表示されているテキストエディタに張り付ける
12. コードを**編集するたび**に、テキストエディタ上部にある歯車のビルドボタンをクリックし、実行ファイルを作る
13. 画面下部のコンソールウィンドウにエラーメッセージが表示されていなければ、`Reload`する
14. 画面中央左の`TinkerbotsBase`から`controller`をクリックし、`Select…`から適応したいコードを選択そ、OKをクリック
15. 上書き保存し再生すれば、ロボットがコードに命令された適切な動きをするはずである



> [!NOTE]
> 視点移動の方法
> - 左クリックしながらドラッグ
>   →視点の角度調整
> - 右クリックしながらドラッグ
> 　→視点の平行移動
> - ホイール
> 　→視点の距離を調整