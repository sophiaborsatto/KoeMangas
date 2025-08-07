# KoeMangas

## Visão Geral

* **Problema:** Interesse e acessibilidade à leitura de mangás.
* **Solução:** Software que narra os painéis e diálogos dos mangás de forma dinâmica, com modos de leitura tradicional, quadro a quadro e imersivo.
* **Usuários e Clientes:** Deficientes visuais, consumidores da cultura oriental, escritores de mangá e dubladores.
* **Recursos Principais:** Narração de textos por IA, catálogo de títulos, sistema de contribuições da comunidade, interface de assinatura.
* **Canais:** Lojas físicas de cultura oriental, redes sociais, organizações de apoio a deficientes visuais.
* **Custo e Receita:** Equipe de desenvolvimento, licenças, parcerias com dubladores. Receita por assinatura mensal e compras avulsas.

---

## Nível 01

* **Nome do Sistema:** KoeMangas
* **Objetivo do Sistema:** Incentivar e facilitar o acesso a mangás, com foco em acessibilidade e imersão.
* **Usuários Principais:** Leitores de mangá e pessoas com deficiência visual.
* **Principais Funcionalidades:** Narração de diálogos e descrição de imagens, modos de leitura adaptáveis (tradicional, quadro a quadro, imersivo).
* **Problema que Será Resolvido:** Falta de acessibilidade e imersão na leitura de mangás.
* **Recursos Desejados:** Processo automático de segmentação de quadros, transições suaves entre cenas, geração de áudio para narração e efeitos sonoros.
* **Plataforma:** Web (Angular) e Mobile (Kotlin / iOS opcional).
* **Prazos e Expectativas:** 10 meses para MVP funcional.

---

## Requisitos Funcionais (RF)

1. **RF01 – Compatibilidade com Leitores de Tela**
   Suporte total a NVDA, JAWS, VoiceOver e outros.

2. **RF02 – Descrição de Imagens**
   Textos alternativos para todos os quadros.

3. **RF03 – Modo de Áudio Descritivo**
   Narração de falas e descrição de cenas em áudio.

4. **RF04 – Acesso ao Catálogo de Mangás**
   Busca e navegação por gênero, popularidade e acessibilidade.

5. **RF05 – Favoritar Mangás**
   Marcar favoritos e gerenciar biblioteca pessoal.

6. **RF06 – Continuar de Onde Parou**
   Salvamento automático do progresso de leitura.

7. **RF07 – Personalização da Experiência**
   Ajustes de velocidade de áudio, tamanho de fonte, contraste, etc.

8. **RF08 – Cadastro e Login de Usuários**
   Registro de conta, autenticação e recuperação de senha.

9. **RF09 – Suporte a Comentários e Avaliações**
   Comentários acessíveis e avaliações de títulos.

10. **RF10 – Contribuição da Comunidade**
    Permitir sugestões de descrições e correções colaborativas.

---

## Requisitos Não Funcionais (RNF)

1. **RNF01 – Acessibilidade (WCAG 2.1 AA)**
   Conformidade com padrões de acessibilidade.

2. **RNF02 – Compatibilidade com Navegadores**
   Suporte a Chrome, Firefox, Safari e Edge.

3. **RNF03 – Tempo de Resposta**
   Carregamento em até 3s em conexão padrão.

4. **RNF04 – Escalabilidade**
   Suporte a alta simultaneidade sem degradação.

5. **RNF05 – Segurança de Dados**
   Criptografia e práticas de segurança para dados sensíveis.

6. **RNF06 – Suporte Responsivo**
   Layout adaptável a desktop, tablet e mobile.

7. **RNF07 – Facilidade de Manutenção**
   Código limpo, documentado e modular.

8. **RNF08 – Disponibilidade**
   Sistema online 24/7 com SLAs definidos.

9. **RNF09 – Usabilidade para Deficiência Visual**
   Interface intuitiva, navegação por atalhos e suporte a alto contraste.

---

## Atores do Sistema

| Ator                               | Responsabilidades / Interações                                                                                                   |
| ---------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| **Visitante (Opcional)**           | Navega catálogo, vê prévias e capas, pode se cadastrar.                                                                          |
| **Usuário (Leitor)**               | Acessa capítulos, salva favoritos, gerencia biblioteca, escolhe modo de leitura, configura acessibilidade e narração automática. Mesmas ações do leitor, com foco em narração sincronizada, descrição de imagens e navegação por teclado/leitores de tela. |
| **Dublador (Voice Actor)**         | Cadastra-se, escolhe mangás/quadros, submete arquivos de voz, revisa aprovações e constrói portfólio.                            |
| **Editor / Curador de Conteúdo**   | Faz upload de mangás e metadados, aprova ou rejeita dublagens, gerencia licenças e destaques.                                    |
| **Administrador do Sistema**       | Monitora e mantém infra, configura integrações (IA, pagamento), gerencia permissões e políticas de segurança.                    |

> *O sistema também interage com repositórios de editoras, serviços de notificação (e-mail/SMS) e CDNs para entrega de mídia.*

---

## Esboço da Tela Principal (Web)

<img width="353" height="780" alt="Esboço da tela principal do KoeMangas" src="https://github.com/user-attachments/assets/ff31f78a-89e1-4494-b646-22548fbfa997" />

---

*Este README serve como base para todo o ciclo de desenvolvimento e alinhamento de equipe.*
