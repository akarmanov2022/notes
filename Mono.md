[`Mono`](https://projectreactor.io/docs/core/release/api/reactor/core/publisher/Mono.html) - издатель Reactive Streams с базовыми `rx` операторами, который выдает не более одного элемента через сигнал `onNext`, и завершается сигналом `onComplete` или выдает `onError`.

`Class Mono<T>`

![[Pasted image 20240408143343.png]]

`rx` операторы `Mono` будут предлагать псевдонимы типа `Mono<T>`, чтобы сохранить свойство *Не более одного* результирующего `Mono`.

`Mono<Void>` следует использовать для издателя, который просто завершается без какого-либо значения.