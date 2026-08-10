# RoomMatch

## ODS Relacionado
**ODS 11 – Cidades e Comunidades Sustentáveis**
*(Meta 11.1: Garantir o acesso de todos à habitação segura, adequada e a preço acessível, e à urbanização inclusiva)*

---

## O que é o Produto
Uma plataforma web interativa estilo "Tinder de Moradia Compartilhada" para a Região Metropolitana de Campinas. O produto conecta jovens trabalhadores, estagiários e estudantes que buscam quartos, kitnets ou parceiros para dividir aluguel com pessoas de perfil compatível, considerando suas rotinas, orçamento e rotas de transporte para faculdades ou centros de trabalho.

---

## Principais Funcionalidades para o Usuário

1. **CardSwipe de Afinidade e Tags de Estilo de Vida:**
   - Algoritmo de *match* tipo Tinder baseado em hábitos diários e estilo de vida.
   - Filtros dinâmicos por **Tags de Convivência**: `Pet Friendly`, `420 Friendly`, `Vegetariano/Vegano`, `Silêncio Noturno`, `LGBTQIA+ Safe`, `Home Office / Estudo Intensivo`, `Sem Festas / Social Moderado`.

2. **Roteirizador Multimodal de Mobilidade Urbana:**
   - Cálculo da distância e tempo de deslocamento do imóvel até o destino do usuário (faculdade, curso ou local de trabalho).
   - Integração de rotas a pé, de bicicleta, por linhas de ônibus municipais/intermunicipais e pontos de integração da RMC.

3. **Mural Interativo de Vagas e Imóveis Compartilhados:**
   - Vitrine de anúncios para quartos individuais, compartilhados, kitnets ou vagas em repúblicas/casas.
   - Transparência total no valor do rateio (aluguel + IPTU + condomínio + contas de consumo) e visualização do perfil dos atuais moradores.

4. **Simulador de Auxílios e Incentivos Habitacionais:**
   - Ferramenta que cruza o perfil socioeconômico e renda do usuário para verificar elegibilidade a bolsas permanência/auxílio-moradia universitários e programas sociais municipais de aluguel/habitação.

---

## Fonte de Dados Públicos Utilizada
- **GTFS / APIs de Transporte Público RMC:** Dados Abertos da EMDEC (Campinas) e da EMTU (linhas intermunicipais da Região Metropolitana de Campinas).
- **OpenStreetMap / Malha Viária Digital:** Dados geoespaciais abertos para cálculo de rotas a pé, ciclovias e raios de proximidade em bairros e distritos da região.
- **Portal da Transparência / Dados do CadÚnico:** Indicadores socioeconômicos e critérios de programas de habitação social e permanência estudantil regionais.
