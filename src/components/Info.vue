<template>
  <v-card color="black" height="3200">
    <div class="ml-16 mt-16">
      <Avatar />
    </div>

    <v-container>
      <v-card color="blue-grey darken-3" style="margin-left: 36%">
        <!-- Conteúdo da página -->
        <v-container>
          <v-container>
            <h1 class="font-weight-medium white--text">
              matheus.alves.stela@gmail.com<br />
              (11) 94968-3673<br />
              26 anos<br />
              São Paulo - SP<br />
              Bairro: Itaquera
            </h1>
          </v-container>
        </v-container>
      </v-card>
    </v-container>

    <v-container>
      <v-card color="blue-grey darken-3" style="margin-right: 32%">
        <!-- Conteúdo da página -->
        <v-container>
          <v-container>
            <h1 class="font-weight-medium white--text">
              Atendente junior<br />
              Contax Mobitel S.A.<br />
              set. 2017 - dez. 2017 - 4 meses<br /><br />
              Atuei com a interface do sistema de telemarketing recebendo
              ligações dos clientes santander e solucionando seus problemas ou
              transferindo-os para o atendimento personalizado. Em suma, efetuei
              a personalização do atendimento juntamente com informações de
              outros setores.
            </h1>
          </v-container>
        </v-container>
      </v-card>
    </v-container>

    <v-container>
      <v-card color="blue-grey darken-3" style="margin-left: 40%">
        <!-- Conteúdo da página -->
        <v-container>
          <v-container>
            <h1 class="font-weight-medium white--text">
              Estagiário<br />
              Amplacon impermeabilizações e comércio Eireli<br />
              Empresa do setor de construção civil<br />
              abr. 2013- out. 2013 - 7 meses<br />
              Belém - São Paulo
            </h1>
          </v-container>
        </v-container>
      </v-card>
    </v-container>

    <v-container>
      <v-card color="blue-grey darken-3" style="margin-right: 28%">
        <!-- Conteúdo da página -->
        <v-container>
          <v-container>
            <h1 class="font-weight-medium white--text">
              Estagiário<br />
              Secretaria municipal de Dirteitos Humanos e Cidadania<br />
              Prestação de contas (Contabilidade)<br />
              abr. 2014 - abr. 2016 - 2 anos<br /><br />
            </h1>
          </v-container>
        </v-container>
      </v-card>
    </v-container>

    <v-container>
      <v-card color="blue-grey darken-3" style="margin-left: 25%">
        <!-- Conteúdo da página -->
        <v-container>
          <v-container>
            <h1 class="font-weight-medium white--text">
              <div style="text-align: center">Sobre</div>
              <br />
              Formado em Administração de empresas como Bacharel, atualmente
              cursando graduação em análise e desenvolvimento de sistemas. Em
              busca da primeira experiência na área.
              <br /><br />
              Técnico administrativo pelo curo técnico de administração - Etec
              de Itaquera
              <br /><br />
              Atualmente cursando Análise e Desenvolvimento de Sistemas, com
              previsão de término para Junho de 2022
            </h1>
          </v-container>
        </v-container>
      </v-card>
    </v-container>

    <v-container>
      <v-card color="blue-grey darken-3" style="margin-right: 36%">
        <!-- Conteúdo da página -->
        <v-container>
          <v-container>
            <h1 class="font-weight-medium white--text">
              <div>Observações</div>
              <br />
              tenho experiência com liderança de equipes usando a metodologia
              SCRUM somente com projetos acadêmicos, sei inglês intermediário,
              tenho experiência com rotinas administrativas e contábeis, mas me
              interessei pela área de TI pela criação de aplicativos e pelo
              envolvimento no contexto histórico atual, procuro observar a todo
              momento tecnologias novas e inovadoras para aperfeiçõar minhas
              técnicas em desenvolvimento web, mas me interesso por áreas de
              criação de jogos ou desenvolvimento android.
            </h1>
          </v-container>
        </v-container>
      </v-card>
    </v-container>
  </v-card>
</template>
`
<script>
import Avatar from "./Avatar";

export default {
  name: "Info",
  components: {
    Avatar,
  },
};
</script>