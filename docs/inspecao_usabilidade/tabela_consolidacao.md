### [Voltar](/docs/inspecao_usabilidade/relatorio_inspecao.md)
### 3.5 – Consolidação (ou Priorização)

| Heurísticas violadas | Quantidade |
|----------------------|------------|
| Visibilidade do estado do sistema (H1) | 3 |
| Correspondência entre o sistema e o mundo real (H2) | 6 |
| Controle e liberdade do usuário (H3) | 9 |
| Consistência e padronização (H4) | 8 |
| Prevenção de erros (H5) | 3 |
| Reconhecer ao invés de relembrar (H6) | 2 |
| Flexibilidade e eficiência de uso (H7) | 6 |
| Estética e design minimalista (H8) | 3 |
| Ajudar os usuários a reconhecerem, diagnosticar e corrigir erros (H9) | 3 |
| Ajuda e documentação (H10) | 2 |

---

| ID | Descrição do problema                                                                                                                        | Classificação  |
|----|----------------------------------------------------------------------------------------------------------------------------------------------|----------------|
| 1  | Ícones de sino, coração e carrinho não têm descrição, dificultando o entendimento do usuário.                                                | Defeito real   |
| 2  | "Compre por categoria" não apresenta um design minimalista, exibindo muitos produtos sem organização clara.                                  | Defeito real   |
| 3  | Ao clicar em uma das categorias, não existe o filtro de produtos e subcategororias.                                                          | Defeito real   |
| 4  | Na opção "Exibir mais", ao escolher uma categoria, aparecem subcategorias em idioma diferente do sistema.                                    | Defeito real   |
| 5  | Nas opções "Tendências", "Moda", "Acessórios para bebês", "Acessórios Pet", ao clicar em uma subcategoria, o menu não desaparece.            | Defeito real   |
| 6  | O botão "Entrar" está sem descrição clara e descentralizado na tela de login.                                                                | Defeito real   |
| 7  | Ao rolar a página para baixo, há demora no carregamento de novos produtos.                                                                   | Defeito real   |
| 8  | A opção "Contato, políticas & muito mais" frequentemente fica sob a barra de URL, inviabilizando seu acesso.                                 | Defeito real   |
| 9  | A seção "Contato, políticas & muito mais" apresenta design incompreensível, com palavras quebradas.                                          | Defeito real   |
| 10 | Ao adicionar um produto no carrinho, a aba "Carrinho" não desaparece da lateral direita.                                                     | Defeito real   |
| 11 | O menu que aparece ao passar o mouse sobre o ícone de usuário desaparece facilmente ao mover o cursor, dificultando a seleção de opções.     | Defeito real   |
| 12 | Na aba "Carrinho", não há opção para excluir itens ou ajustar quantidades diretamente.                                                       | Defeito real   |
| 13 | Há uma barra de porcentagem em volta do ícone do carrinho ao adicionar itens, sugerindo um limite de produtos que não existe.                | Defeito real   |
| 14 | No campo "Linha de endereço 1", não está claro quais informações devem ser inseridas.                                                        | Defeito real   |
| 15 | No campo "Cidade", não há opção de auto completar ou sugestão de cidades.                                                                    | Defeito real   |
| 16 | Nos campos "Código postal/CEP" e "Número de telefone", é possível inserir caracteres inválidos, como letras ou números excessivos.           | Defeito real   |
| 17 | Ao clicar em "Finalizar" sem preencher todas as informações essenciais, o sistema não permite prosseguir sem indicar claramente os erros.    | Defeito real   |
| 18 | Não há opção para voltar à tela anterior durante o processo de compra ou navegação.                                                          | Defeito real   |
| 19 | Ausência de sugestao de produtos similares para comparação antes da finalização da compra.                                                   | Falso Positivo |
| 20 | Na "Lista de Desejos", a opção de editar é confusa, sugerindo funcionalidades não disponíveis, como alterar quantidade ou modelo do produto. | Defeito real   |
| 21 | Nas configurações da conta, não existe opção de gênero neutro ou outras identidades de gênero.                                               | Falso Positivo |
| 22 | A opção "Gerenciar conta" não é autoexplicativa e apresenta ações como excluir ou desativar conta sem esclarecimento.                        | Defeito real   |
| 23 | Problemas de adaptação ao tamanho do monitor, resultando em palavras sobrepostas e layout quebrado.                                          | Defeito real   |
| 24 | O site mistura inglês e português em diversas telas e opções.                                                                                | Defeito real   |
| 25 | Falta de recursos de acessibilidade para pessoas com deficiência.                                                                            | Defeito real   |
| 26 | O nome da opção "Guia" é enganoso, direcionando o usuário para uma aba de compras em vez de oferecer ajuda.                                  | Defeito real   |
| 27 | Na seção "Entre em Contato", o design é inconsistente, com áreas em branco e conteúdo irrelevante, como um vídeo sem relação com a página.   | Falso Positivo |
| 28 | Ao clicar em "Ajuda com um pedido recente", o usuário é direcionado apenas para um chatbot, sem outras opções de suporte disponíveis.        | Falso Positivo |
| 29 | A opção "Denunciar" leva a um formulário em inglês, apesar do restante do site estar em português.                                           | Defeito real   |
| 30 | Existem duas opções chamadas "Visão Geral" com funcionalidades diferentes, causando confusão.                                                | Defeito real   |
| 31 | Avaliações de clientes apresentam comentários em idiomas diferentes do configurado pelo usuário, sem tradução.                               | Defeito real   |
| 32 | Inconsistência no idioma padrão da página em diversas seções, como "Diretrizes da Comunidade" e "Acessibilidade".                            | Defeito real   |
| 33 | O filtro "Relacionados" não funciona corretamente em alguns produtos, exibindo itens não relacionados.                                       | Defeito real   |
| 34 | Ausência de um botão para voltar ao topo da página ao chegar ao final.                                                                       | Defeito real   |
| 35 | Não há opção de zoom nas imagens dos anúncios, dificultando a visualização de detalhes.                                                      | Defeito real   |
| 36 | Ao adicionar um produto à lista de desejos, o sistema não permite escolher em qual lista adicioná-lo.                                        | Defeito real   |
| 37 | Formulários de endereço permitem inserir qualquer tipo de dado, sem validação ou campos específicos para número, rua e bairro.               | Defeito real   |
| 38 | Falta de validação nos formulários para se tornar vendedor, exceto no campo "Telefone Comercial".                                            | Defeito real   |
| 39 | Ícone de "Promoção Relâmpago" utiliza imagem inadequada (CD em vez de um raio), confundindo o usuário.                                       | Falso Positivo |
| 40 | Opções ou textos sobrepostos e cortados em listas de categorias e menus, dificultando a leitura e a navegação.                               | Defeito real   |
| 41 | Campos de senha não permitem visualizar a senha inserida, impossibilitando a verificação antes de confirmar.                                 | Defeito real   |
| 42 | Impossibilidade de cancelar pedidos após a compra e acompanhar o status dos mesmos.                                                          | Defeito real   |
| 43 | Falta de feedback ou indicador visual durante carregamentos e buscas, deixando o usuário sem saber o que está acontecendo.                   | Falso Positivo |
| 44 | Opções de pagamento limitadas dependendo da localização do usuário, impossibilitando a conclusão de compras.                                 | Defeito real   |
| 45 | Mensagens de erro genéricas que não fornecem instruções claras sobre como corrigir problemas.                                                | Falso Positivo |
| 46 | Itens duplicados podem aparecer no carrinho ou na compra, indicando possível bug no sistema.                                                 | Defeito real   |
| 47 | Descrições de produtos vagas ou imprecisas, não oferecendo detalhes suficientes para o usuário entender o que está comprando.                | Falso Positivo |
| 48 | Falta de assistência para novos usuários em termos de tutoriais ou dicas contextuais.                                                        | Defeito real   |
| 49 | Excesso de informações irrelevantes nas descrições dos produtos, não contribuindo para a decisão de compra.                                  | Defeito real   |
| 50 | Variabilidade no suporte e funcionalidades conforme o idioma selecionado, com suporte limitado para português.                               | Defeito real   |

---

| Severidade | Quantidade |
|------------|------------|
| 0 - Falso-Positivo | 8 |
| 1 - Cosmético | 0 |
| 2 - Leve | 5 |
| 3 - Grande | 8 |
| 4 - Catastrófico | 7 |

### [Voltar](/docs/inspecao_usabilidade/relatorio_inspecao.md)
