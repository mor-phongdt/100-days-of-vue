[vetur]: https://marketplace.visualstudio.com/items?itemName=octref.vetur
[vscode]: https://code.visualstudio.com/
[wstorm]: https://www.jetbrains.com/webstorm/download/#section=linux
[vue]: https://marketplace.visualstudio.com/items?itemName=jcbuisson.vue
[vue3]: https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar
[vetur]: https://marketplace.visualstudio.com/items?itemName=octref.vetur
[vuesnippet]: https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets
[atom]: https://marketplace.visualstudio.com/items?itemName=akamud.vscode-theme-onedark
[bracketPair]: https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2
[indentRainbow]: https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow
[icontheme]: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme
[todoHighlight]: https://marketplace.visualstudio.com/items?itemName=wayou.vscode-todo-highlight
[autoCloseTag]: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag
[autoCompleteTag]: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-complete-tag
[autoRenameTag]: https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag
[Auto Import]: https://marketplace.visualstudio.com/items?itemName=steoates.autoimport
[Path Intellisense]: https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense
[Vue Peek]:https://marketplace.visualstudio.com/items?itemName=dariofuzinato.vue-peek
[Css Peek]:https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek
[Visual Studio IntelliCode]: https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode
[Code Spell Checker]:https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker
[JavaScript Booster]: https://marketplace.visualstudio.com/items?itemName=sburg.vscode-javascript-booster
[Indenticator]: https://marketplace.visualstudio.com/items?itemName=SirTori.indenticator
[Import Cost]: https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost
[GitLens]: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens
[ESLint]: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint
[TSLint]:https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-tslint-plugin
[Prettier]:https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode
[SCSS IntelliSense]: https://marketplace.visualstudio.com/items?itemName=mrmlnc.vscode-scss
[Tabnine]:https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode
[NodeJS]: https://nodejs.org/en/
[Vue CLI]: https://cli.vuejs.org/guide/installation.html
[Vue]:https://vuejs.org/v2/guide/installation.html
# Day 001: Installation



## Giới thiệu:
Hôm nay mình sẽ chia sẻ cách mình setup môi trường làm việc, extension , phần mềm liên quan mà mình có sử dụng (Có thể cái này mọi người đã biết rồi có thể next sang bài khác) để có thể support cho công việc của mình một các tốt nhất.

## Thực hiện:
### Enviroment:
- Khi setup môi trường làm việc thì việc đầu tiên là chọn và cái đặt hệ điều hành thì mình chọn Ubuntu là môi trường phổ thông nhất cho mọi người, bất kì ai cũng có thể tiếp cận được. Rất dễ cài các thư viện, các phần mềm hỗ trợ việc coding, sử hữu terminal mạnh mẽ. Còn về window thì hơn cùi vì 1 số cái chưa được hỗ trợ,  Power Shell thì không thể nào bằng được Terminal.Nếu có tài chính dư rả thì mọi ng có thể đầu tư Macbook để được sử dụng MacOS - Đây là sự lựa chọn đối với mình là hoàn hảo nhất vì nó có thể coi là sự dung hoà của  hai hệ điều hành nêu ở trên.
- Tiếp theo là đến các package bắt buộc để có thể thực hiện việc coding
  - [NodeJS]: Về NodeJs mọi người nên chú ý version của nó vì có thể mỗi dự án sẽ ưu cầu 1 version NodeJs. Vậy nên nếu được thì hãy sẽ dụng NBM để cài đặt, quản lý các version của NodeJS
  - NPM: Đây là công cụ quản lý cũng như cài đặt các thư viện Javascript (Ngoài ra còn có yarn, tuỳ project và sở thích mỗi người để lựa chọn), Để cài đặt chạy command dưới đây:
    ````
    npm install npm@latest -g
    ````
  - [Vue]: Đây là package sẽ được cài global trên máy để có thể chạy một project VueJs
    ```
    npm install vue
    ```
  - [Vue CLI]: Đây là một package giúp chúng ta có thể thiết lập nhanh một project vue chưa đến 1 phút. Nó tích hợp tất cả vuex, vue-router, vuetify,.. một lúc luôn mà k cần phải mất công cài đặt, Dưới đây là command để cài đặt [Vue CLI]:
    ```
    npm install -g @vue/cli
    ```
    Để có thể tạo 1 project VueJs đơn giản thì có thể dùng command sau:

    ```
    vue create hello-world
    ```

### IDE/Editor:
Hiện tại đang có 2 IDE nổi bất nhất hiện nay dành cho các Frontend Dev là Visual Studio Code vá Webstorm. Mình đã dùng qua cả 2 và vẫn trung thành với Vscode vì gọn nhẹ, dễ customize, có nhiều extension hay ho, dễ nhìn, dễ dùng dễ tiếp cận với người mới bắt đầu. Còn Webstorm từ hệ sinh thái JetBrain thì quá tuyệt với rồi, gợi ý code rất nhanh =)), có hiển thị label cho các biến,các function, nhưng hơi khó tiệp cận với người mới vì mất tiền bản quyền cũng như giao diện phức tạp hơn. Nếu được thì mình nghĩ kết hợp cả 2 sẽ là một phương án tối ưu nhất hehe (Còn lý do tại sao thì mình nghĩ các bạn nên trải nghiệm thử rồi sẽ biết tại sao và tư đưa ra được solution cho bản thân mình).

- [Visual Stuido Code][vscode]
- [WebStorm][wstorm]
### Extension (Dành cho vscode):
- [Vue][vue], [Vue3][vue3], [Vetur][vetur], [Vue VSCode Snippet][vuesnippet]: đây là một số các exten cần thiết để vscode hiểu syntax của Vue, gợi ý code của Vue, các snippet dành cho Vue.
- [Atom One Dark Theme][atom], [Material Icon Theme][icontheme]: đây là 2 theme mình dùng cho tương ứng cho IDE và icon của IDE. Mình thấy 2 cái theme này khá là nổi tiếng nhiều ông youtuber cũng dùng 2 cái này, ngoài ra các bọn có thể chỉnh font family và font size cho IDE để nhìn xịn sò hơn.
- [Bracket Pair Colorizer 2][bracketPair], [indent-rainbow][indentRainbow], [TodoHighlight][todoHighlight], [Indenticator]: Những extensions này giúp mình "make color" cho Vscode của mình. 
- [AutoCloseTag][autoCloseTag], [AutoCompleteTag][autoCompleteTag], [AutoRenameTag][autoRenameTag]: Bộ 3 này giúp mình code các thẻ html nhanh hơn 1 cách đáng kể, 3 cái tên đều nói lên cách 3 extensions này hoạt động thế nào.
- [ESLint], [Prettier]: đây là bộ đôi không thể thiếu để mình có thể format theo các chuẩn code đã được đặt ra từ đầu mỗi dự án. (Nếu ai có sử dụng Typescpirt thì có thể sử dụng thêm cả [TSLint]).
- [Visual Studio IntelliCode], [Path Intellisense], [SCSS IntelliSense], [Tabnine]: các extension này sẽ đưa ra các gợi ý về syntax code, đường dẫn file. Đặc biệt Tabnine còn sử dụng AI để đưa ra cho mình những đoạn code phù hợp nữa. Qua việc sử dụng các extensions này thì mình cải thiện được hiệu quả công việc đến 30%.
- [Code Spell Checker]: đây là một extension khá hay giúp mình soát chính tả những từ tiếng Anh đã viết. Lúc chưa sử dụng extension này mình có dính 1 case là đặt tên biến chỗ là question, chỗ khác là qyestion (do tay nhanh hơn não=)))) rồi 1 thời gian sau phát sinh ra bug , rồi kiểm tra đi kiểm tra lại thì k thấy bussiness logic sai ở đâu cả. Ngồi cả buổi toét mắt ra thì mới thấy hoá ra mình viết sai chính tả híc.
- [Vue Peek]: giúp mình có có thể đi đấy các file chứ các component 1 cách như chóng chứ k phải ngồi search lại tên file.
- [Css Peek]: cũng tương tự Vue Peek thì extension này giúp mình có thể di chuyển đến file chứa class đấy 1 cách nhanh chóng hơn.
- [GitLens]: đối với mình gitLens là 1 extension k thể thiếu khi sử dụng git, ngoài ra các bạn có thể sử dụng các phần mềm ở ngoài như kiểu Smart Git.

