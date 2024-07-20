# IDine

IDine é um aplicativo de apoio para garçons e equipe de cozinha, projetado para facilitar a comunicação e gestão de pedidos dentro de um restaurante. O aplicativo permite aos garçons registrar pedidos, enviá-los diretamente para a cozinha, acompanhar o status dos pedidos e notificar quando estiverem prontos para servir.

Esse aplicativo foi desenvolvido durante a disciplina de QXD0102 - DESENVOLVIMENTO DE SOFTWARE PARA DISPOSITIVOS MÓVEIS na Univeridade Federal do Ceará

## Funcionalidades

1. **Tela de Login e Autenticação**:
    - Autenticação para garçons e equipe da cozinha usando Firebase Authentication.

2. **Tela de Mesas**:
    - Exibição das mesas do restaurante com status (livre, ocupada, aguardando pedido, pedido em preparo, pronto para servir) usando RecyclerView e CardView.

3. **Tela de Pedidos**:
    - Listagem de itens do cardápio com imagens e descrições, permitindo que garçons adicionem itens ao pedido.

4. **Tela de Envio de Pedidos**:
    - Resumo do pedido e botão para enviar o pedido para a cozinha, usando Firebase Realtime Database.

5. **Tela de Status do Pedido**:
    - Atualização em tempo real do status do pedido, notificando os garçons quando estiverem prontos para servir.

6. **Tela de Gestão de Pedidos na Cozinha**:
    - Exibição de pedidos recebidos pela cozinha e atualização do status dos pedidos.

7. **Notificações**:
    - Agendamento de notificações quando um pedido estiver pronto para servir, usando Work Manager.

8. **Histórico de Pedidos**:
    - Visualização do histórico de pedidos pelos garçons e pela equipe da cozinha.

## Tecnologias Utilizadas

- **Kotlin**: Linguagem de programação principal.
- **Android Studio**: IDE utilizada para o desenvolvimento do aplicativo.
- **RecyclerView**: Para exibir listas de itens, como mesas e cardápios.
- **CardView**: Para exibir cada item em uma lista de forma organizada.
- **Firebase Authentication**: Para autenticação de usuários.
- **Firebase Realtime Database**: Para atualização em tempo real dos pedidos.
- **Work Manager**: Para agendamento de notificações.
- **ROOM Database**: Para armazenamento local de dados (opcional).
- **Google Maps API**: Para exibição da localização do restaurante (opcional).

## Instalação

1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/idine.git
   ```
2. Abra o projeto no Android Studio.
3. Configure o Firebase Authentication e Realtime Database no Firebase Console e conecte o projeto Android ao Firebase.
4. Execute o aplicativo em um dispositivo ou emulador Android.

## Estrutura do Projeto


## Contribuições

Contribuições são bem-vindas! Para contribuir, siga os passos abaixo:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nome-da-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça o push para a branch (`git push origin feature/nome-da-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Autor

- **Seu Nome** - [seu-usuario](https://github.com/christianestevam)

---

