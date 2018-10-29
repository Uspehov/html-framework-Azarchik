# html-framework-Azarchik
Были созданы классы container, row, col-md-1 ... col-md-12. 
В разделе Демострация колонок представлены созданные мною колонки от 1 до 12.
Ширина их задавалась с помощью width: calc((100%) / 12).
Колонкам прописан класс float-left. У некоторых корлонок задан класс Float-right.
Для содержимого всех колонок задан класс text-align: center; Красные полосы это класс row.
Колонки адекватно реагируют на зменение разрешения экрана т.к. 
задавались в % а не в пикселях.

Для флексов были реализованы классы  flex, flex-row, flex-column, space-between, y-center, x-start, x-end. 
В разделе демонстрация флексов показано применение этих классов на практике.


var xhr = new XMLHttpRequest()
xhr.open(
  'GET',
  '//developer.nytimes.com/lists.json','key=<0522b6a622be40e8b2d14993b0c82967>',
  true
)
xhr.send()

xhr.onreadystatechange = function() {
  if (xhr.readyState != 4) {
    return
  }

  if (xhr.status === 200) {
    console.log('result', xhr.responseText)
  } else {
    console.log('err', xhr.responseText)
  }
}
ƒ () {
  if (xhr.readyState != 4) {
    return
  }

  if (xhr.status === 200) {
    console.log('result', xhr.responseText)
  } else {
    console.log('err', xhr.responseText)
  }
}
