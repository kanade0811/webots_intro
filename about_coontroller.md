## 1. コントローラ・プログラムの作成と適応

1. コントローラの作成
    1. `Wizards`→`New Robot Controller`を選択
    2. `New controller creation`ではそのまま次へ
    3. `Language selection`では`C`を選択し次へ
    4. `IDE selection`では`Webots (gcc / Makefile)`を選択し、次へ
    5. コントローラー名を入力し、次へ
    6. `Condusion`では`Open (コントローラー名) in Text Editor.`にチェックを入れ終了する
    7. Webotsにて出てきたテンプレートのプログラムを削除する
    8. `my_project`にある`header_generator.bat`をコピーし、`controllers`ファイルを開く
    9. 新しく作成したプログラムのフォルダを開き、`8.`にてコピーした`header_generator.bat`を張りつける
    10. `header_generator.bat`をダブルクリックし、`tinkerbots_utility.c`と`tinkerbots_utility.h`が作成されたことを確認する
    11. `my_project\template.c`をメモ帳で開き、中身のコードをWebotsの画面中央右に表示されているテキストエディタに張り付ける

2. コントローラの適応
    1. 適応させたい`TinkerbotsBase`を展開し、`controller`を選択する。
    2. 画面左下にある`Select…`から、動かさせたいcontrollerを選択する。
    3. `Edit`をクリックすることで画面右のテキストエディタにコードが表示される。



> [!NOTE]
> 視点移動の方法
> - 左クリックしながらドラッグ
>   →視点の角度調整
> - 右クリックしながらドラッグ
> 　→視点の平行移動
> - ホイール
> 　→視点の距離を調整