![Jetpack Compose: Armazenamento de Arquivos Android](https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/assets/35709152/51cd2f77-0f4a-401d-b442-55f591537712)


Projeto para o curso inicial de Armazenamento de Arquivos no Android com Jetpack Compose: Introdução à API MediaStore, SAF (Storage Access Framework), Photo Picker, permissões e sistema de arquivos do Android.



## :hammer: Funcionalidades do projeto
Para simular um aplicativo de troca de mensagens, o Concord, oferece as seguintes telas:

- `Aba inicial`: Exibie uma lista contatos fictícia, cada contato pode ser clicado para abrir o histórico de conversas.
- `Converas (Chat)`: Mostra o histórico de mensagens trocadas, como nosso app não está conectado a uma Web API, é possível apenas fazer o envio delas no momento.
- `Figurinhas (Sticker List)`: Usa o componente [ModalBottomSheet][modalbottomsheet-link] para exibir uma lista de imagens do armazenamento específico ou compartilhado.
- `Seletor de fotos (Photo Picker)`: Usa a UI nativa do Android para exibir imagens salvas no dispositivo.
- `Seletor de arquivos (File Picker)`: Usa a UI nativa do Android para exibir todos arquivos salvos no dispositivo.

https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/assets/35709152/ba4bdc01-92c9-4c15-9662-8e7abce51a55

## 🏠 Arquitetura
* Navigation
* Room Database
* Kotlin Coroutines e Flow
* ViewModel com StateFlow
* Hilt (injeção de dependência)

## ✔️ Outras técnicas e tecnologias utilizadas
* [Photo Picker][photopicker]
* [MediaStore][mediastore]
* [Storage Access Framework (SAF)][SAF]
* Kotlin
* Jetpack Compose
* Compose BOM
* [Coil][coil]
* [LocalDate][localdate] do Java 8+, compatível com versões abaixo do Android 8 graças ao [desugaring support][jdk8desugar]


## 📂 Acesso ao projeto
- Versão inicial: Veja o [código fonte][codigo-inicial] ou [baixe o projeto][download-inicial]
- Versão final: Veja o [código fonte][codigo-final] ou [baixe o projeto][download-final]
- [Arquivos de mídia para testes][arquivos]

## 🛠️ Abrir e rodar o projeto
Após baixar o projeto, você pode abri-lo com o Android Studio. Para isso, na tela de launcher clique em:

“Open” (ou alguma opção similar), procure o local onde o projeto está e o selecione (caso o projeto seja baixado via zip, é necessário extraí-lo antes de procurá-lo). Por fim, clique em “OK” o Android Studio deve executar algumas tasks do Gradle para configurar o projeto, aguarde até finalizar. Ao finalizar as tasks, você pode executar o App 🏆

## 🎯 Desafios
- Carregando Thumbnails - [Veja a solução][desafio]

![gif-desafio-github](https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/assets/35709152/79ae2713-da01-484e-bcb9-8dc7612405c7)

## 📚 Mais informações do curso

Gostou do conteúdo e quer saber mais detalhes? Então [confira o curso na página da Alura](https://www.alura.com.br/curso-online-jetpack-compose-armazenamento-arquivos-android) 😉

[modalbottomsheet-link]: https://developer.android.com/reference/kotlin/androidx/compose/material3/package-summary#ModalBottomSheet(kotlin.Function0,androidx.compose.ui.Modifier,androidx.compose.material3.SheetState,androidx.compose.ui.graphics.Shape,androidx.compose.ui.graphics.Color,androidx.compose.ui.graphics.Color,androidx.compose.ui.unit.Dp,androidx.compose.ui.graphics.Color,kotlin.Function0,kotlin.Function1)
[photopicker]: https://developer.android.com/training/data-storage/shared/photopicker
[mediastore]: https://developer.android.com/training/data-storage/shared/media?hl=pt-br#query-collection
[SAF]: https://developer.android.com/guide/topics/providers/document-provider
[arquivos]: https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/tree/arquivos
                                                                                                                                                                                 
[localdate]: https://developer.android.com/reference/java/time/LocalDate
[jdk8desugar]: https://developer.android.com/studio/write/java8-support#library-desugaring
[coil]: https://coil-kt.github.io/coil/
[codigo-inicial]: https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/commits/projeto-inicial
[download-inicial]: https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/archive/refs/heads/projeto-inicial.zip
[codigo-final]: https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/commits/aula-5
[download-final]: https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/archive/refs/heads/aula-5.zip
[desafio]: https://github.com/alura-cursos/jetpack-compose-armazenamento-arquivos-android/commit/7da97205a4be85f909562111eb1858a32558fc57


