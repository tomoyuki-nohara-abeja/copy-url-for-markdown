# copy-url-for-markdown
Markdown形式でリンクをコピーするブックマークレット

<a href="javascript:javascript%3A(function()%7Bvar Markdown形式のリンクをクリップボードにコピーする%3Dfunction()%7Bvar コピーしたい文字列%3D'%5B'%2Bdocument.title.replace(%2F(%5B%5C%5B%5C%5D%5D)%2Fg%2C'%5C%5C%241')%2B'%5D'%2B'('%2Blocation.href%2B')'%3B%2F* クリップボードにコピーするおまじない *%2F var 引数の文字列をクリップボードにコピーする%3Dfunction(text)%7Bvar ta%3Ddocument.createElement("textarea")%3Bta.value%3Dtext%3Bdocument.body.appendChild(ta)%3Bta.select()%3Bdocument.execCommand("copy")%3Bta.parentElement.removeChild(ta)%3B%7D%3B引数の文字列をクリップボードにコピーする(コピーしたい文字列)%3Bvar myアラートを出して数秒後に消す%3Dfunction(文字列%2C表示時間_msec)%7Bvar p%3Ddocument.createElement('p')%3Bp.innerHTML%3D'クリップボードにコピーしました。※この表示は、0.3秒後に消えます。<br><br>'%2B文字列%3Bdocument.querySelector('body').appendChild(p)%3Bp.style.width%3D'100%25'%3Bp.style.height%3D'auto'%3Bp.style.position%3D'fixed'%3Bp.style.top%3D'0'%3Bp.style.left%3D'0'%3Bp.style.backgroundColor%3D'%23009900'%3Bp.style.color%3D'white'%3Bp.style.padding%3D'20px'%3Bp.style.display%3D'block'%3Bp.style.zIndex%3D'9998'%3BsetTimeout(function()%7Bp.parentNode.removeChild(p)%3B%7D%2C表示時間_msec)%3B%7D%3Bmyアラートを出して数秒後に消す(コピーしたい文字列%2C300)%3B%7D%3BMarkdown形式のリンクをクリップボードにコピーする()%3BMarkdown形式のリンクをクリップボードにコピーする%3Dnull%3B%7D)()%3Bvoid(0);">ブックマークレット</a>


<a href="/">atag</a>
