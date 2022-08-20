Paleta de cores:
Verde pirncipal: #9fa75a
Azul escuro: #242834
Bege: #5e5c5a
Branco: #ffffff
vermelho: #c23234
AHAHHAAHHAHAHA DA LEITADA NA MINHA CARA LOBO MAL <3 8===============D
tela em branco
arrumar o text input






Dtm

import React from 'react';
import { View, SafeAreaView, Text, Dimensions, Image, StyleSheet, ScrollView, ImageBackground, StatusBar } from 'react-native';
import { useNavigation } from '@react-navigation/native';


export default function Ortog() {
const navigation = useNavigation();  
 return (
   <SafeAreaView style={styles.container}><StatusBar backgroundColor={'#9fa75a'}/>
    <ImageBackground style={styles.img} source={require('../../../../assets/ImagemBase.jpg')} />

      <ScrollView style={styles.scroll}>
      
      <View style={styles.all}>
        <View style={styles.track}></View>
        <Text style={styles.h1}>O que é DTM?</Text>
        <Text style={styles.h2}>Existem diversos tipos de tratamentos para as Disfunções Temporomandibulares (DTM). Antes de instituir um determinado tratamento é preciso diagnosticar a causa para que os resultados não sejam imprevisíveis. Os exames clínicos e de imagem, tais como as radiografias panorâmicas, tomografias e ressonância magnéticas, são de extrema importância.</Text>
      </View>
      <View style={{backgroundColor: '#242834'}}>
        <View style={styles.track2}></View>
        <View styles={styles.al2}>
          <Text style={styles.h12}>Pré-operatório</Text>
          <Text style={styles.h4}>Uma vez determinada a necessidade de realizar a Cirurgia Ortognática, o paciente deverá passar em várias consultas conosco, a fim de determinar o que será executado. Em nossa clínica desenvolvemos um planejamento minucioso para a realização da Cirurgia Ortognática. Trata-se de um protocolo em diversas etapas, que incluem desde simulações em 2D personalizadas, moldagens e fotos padronizadas até planejamentos em 3D, nos quais os pacientes podem analisar e discutir, junto com a nossa equipe, o resultado cirúrgico que deseja obter. O bom relacionamento entre o paciente, o cirurgião e a equipe é essencial para que todas as dúvidas sejam esclarecidas e para que haja confiança em todas as partes do tratamento.Como parte da preparação para a cirurgia, o paciente deve realizar exames pré-operatórios (Rx de tórax, Eletrocardiograma, Hemograma), que serão avaliados pelo cirurgião e pelo médico anestesista da equipe.</Text>
          <Text style={styles.h4}></Text>
        </View>
        <View style={styles.track3}></View>
        <View styles={styles.al2}>
          <Text style={styles.tecnica}>Técnica cirúrgica</Text>
          <Text style={styles.tecnicah1}>Utilizamos uma Técnica Minimamente Invasiva que consiste em realizar acessos cirúrgicos menores, com o descolamento cuidadoso dos tecidos e uso de instrumentais específicos que promovem um trauma cirúrgico menor. Todos os acessos são realizados por dentro da boca, portanto, não há cicatrizes. Essas abordagens fazem com que os pacientes tenham pós-operatórios melhores, com menos inchaço, menores chances de parestesia e uma recuperação mais rápida.</Text>
        </View>


      </View>
      <Text> {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} </Text>
      <Text> {'\n'}  </Text>
    </ScrollView>

   </SafeAreaView>
  );
}
const { height } = Dimensions.get('window')
const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#242834',
    height: height,
  },
  scroll:{
    width: '100%',
    height: '100%',
    bottom: '0%',
    
    position: 'absolute',
  },
  img:{
    width: '100%',
    height: 210,
    position: 'relative',
  },
  all:{
    top: '7.5%',
    borderTopRightRadius: 21,
    borderTopLeftRadius: 21,
    backgroundColor: '#242834',
    width: '100%',
    alignItems:"center",
    height: 550,
    position: 'relative',
  },
  al2:{
    top: 20,
    backgroundColor: '#242834',
    width: '100%',
    height: '100%',
    alignItems:"center",
    height: 900,
    position: 'relative',
  },
  track: {
    backgroundColor: '#9fa75a',
    width: '20%',

    top: '0.5%',
    height: '0.7%',
    borderRadius: 20,
  },
  track2: {
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    bottom: '3%',
    height: '0.5%',
    borderRadius: 20,
  },
  track3: {
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '0%',
    height: '0.5%',
    borderRadius: 20,
  },
  h1: {
    color: '#FFF',
    fontSize: 20,
    color: '#9fa75a',
    top: '1.4%',
    fontFamily: "PoppinsSemiBold",
    backgroundColor: '#242834',
  },
  h12: {
    color: '#FFF',
    fontSize: 24,
    color: '#9fa75a',
    bottom: '4%',
    fontFamily: "PoppinsSemiBold",
    left: '25%',
  },

  h2: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '0%',
    width: '90%',
    top: '4%',
    fontFamily: "PoppinsRegular", 
  },
  h3: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '0%',
    width: '90%',
    top: '4%',
    fontFamily: "PoppinsRegular", 
  },
  h4:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    bottom: '3%',
    fontFamily: "PoppinsRegular", 
  },
  tecnica: {
    fontSize: 24,
    color: '#9fa75a',
    top: '3%',
    fontFamily: "PoppinsSemiBold",
    left: '22%',
  },
  tecnicah1: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '5%',
    fontFamily: "PoppinsRegular", 
  },
  h5:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '1%',
    fontFamily: "PoppinsRegular", 
  },
  duraçao:{
    fontSize: 22,
    color: '#9fa75a',
    top: '23%',
    fontFamily: "PoppinsSemiBold",
    left: '12%',
  },
  duraçaotrack:{
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '3.2%',
    height: '0.5%',
    borderRadius: 20,
  },
  duraçaoh1:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '25%',
    fontFamily: "PoppinsRegular", 
  },
  pos:{
    fontSize: 24,
    color: '#9fa75a',
    top: '9.5%',
    fontFamily: "PoppinsSemiBold",
    left: '27%',
  },
  postrack:{
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '3%',
    height: '0.5%',
    borderRadius: 20,
  },
  posh1:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '10%',
    fontFamily: "PoppinsRegular", 
  }
});













Pos Operatório

import React from 'react';
import { View, SafeAreaView, Text, Dimensions, Image, StyleSheet, ScrollView, ImageBackground, StatusBar } from 'react-native';
import { useNavigation } from '@react-navigation/native';


export default function Pos() {
const navigation = useNavigation();  
 return (
   <SafeAreaView style={styles.container}><StatusBar backgroundColor={'#9fa75a'}/>
    <ScrollView style={styles.scroll}>
      
      <Text style={styles.topico}>{'\n'}{'\n'}Higiene Oral</Text>
      <Text style={styles.texto}>Escovar os dentes será trabalhoso nas primeiras semanas, mas é necessario uma higiene oral bem rigorossa para prevenir infecções. Você vai sentir dificuldade para usar sua escova de dente, então use uma escova menor com cerdas muito macias. Por causa do inchaço você pode sentir dificuldade de colocar a escoava dentro da boca, então, com o dedo, afaste a bocheca e coloque a escova dentro da boca; durante o vai e vem com a escova faça o movimento bem devagar, sem força, mas é importante que alcance os dentes do fundo. Enxague bem com água e após, faça bochechos com antisséptico bucal várias vezes ao dia.<Text style={styles.aviso}> Faça sempre uma higiene horal depos de comer. </Text></Text>
      <Text style={styles.topico}>Dieta</Text>
      <Text style={styles.texto}>Nos primeiros dias:
      {'\n'} - Dieta líquida fria (Sopa batida de legumes, verduras, cereais e carne pelo menos 2 vezes ao dia);
      {'\n'}- Procure beber bastante líquido (Água, sucos, água de coco) cerca de 1,5 litros/dia;
      {'\n'} - Preparações com leite (Achocolatado, leite com frutas, mingau ralo) ou suplementos de 2 a 3 vezes por dia.{'\n'}{'\n'}
Se você sentir dificuldade em utilizar o canudo, pode usar um copinho de café, uma colher ou uma seringa para auxiliar a colocar os líquidos dentro da boca para engolir.
{'\n'}{'\n'} <Text style={styles.aviso}>
Procure respeitar a aceitação do seu corpo com a quantidade de comida e lembre-se de comer em 3 em 3 horas </Text>
{'\n'}{'\n'}

Depois do período de dieta liquida, você deve passar para pastosa liquida (como a papinha de bebê) por 2 a 3 semanas; depois pastosa com mais consistência (alimentos amassados) por
2 a semanas; e dieta com alimentos sólidos macios (que não exigem força para morder) por 2 a 3 semanas; e em 90 dias Você estará comendo alimentos com a mesma consistência de antes 
da cirurgia.{'\n'}</Text>

<Image source={require('./../../../../assets/Pos/Tabela.png')} style={styles.tabela}/>

      <Text style={styles.topico}>Abertura da boca</Text>
      <Text style={styles.texto}>Siga as orientações do cirurgião e do ortodontista para uso e troca dos elásticos conforme sua evolução no pósoperatório e para realizar os exercícios para retornar a abrir a boca normalmente em 6 semanas.
      {'\n'}
<Text style={styles.aviso}>O excesso de força para a abertura da boca e a mastigação, pode prejudicar a estabiladade da nova posição das estruturas de sua face .</Text></Text>
      <Text style={styles.topico}>Aplicação de gelo</Text>
      <Text style={styles.texto}>Você poderá aplicar uma bolsa térmica de gelo no rosto para ajudar a diminuir o inchaço, por um período de 20 minutos com intervalo de 10 a 15 minutos entre cada aplicação de gelo.
Ou então, coloque vários cubos de gelo em uma toalha e quando for colocar sobre o rosto cubra primeiro a pele do rosto com um tecido.{'\n'} <Text style={styles.aviso2}>(Tempo superior a 20 minutos pode machucar a pele, esteja a atento ao tempo de permanência do gelo.)</Text></Text>
      <Text style={styles.topico}>Exercícios</Text>
      <Text style={styles.texto}>Para auxiliar a recuperação da cirurgia e da mobilidade e sensibilidade da região, você pode realizar alguns exercícios em casa após liberação do cirurgião.</Text>
      <Text style={styles.topico}>Com a bochecha:</Text>
      <Text style={styles.texto}>Coloque um pouco de ar dentro da boca e empurre o ar para lado direito e esquerdo dentro da boca, como se você fizesse uma bola na bochecha. Repita algumas vezes durante o dia.</Text>
      <Text style={styles.topico}>Com a língua:</Text>
      <Text style={styles.texto}>Tente passar a ponta da língua nos çábios superior e inferior, sem forçar a abertura da boca, se não estiver com a sensibilidade da região, você pode fazer em frente do espelho para vizualizar. Repita algumas vezes durante o dia. Se estiver conseguindo respirar pelo nariz, procure manter os lábios fechados e a língua no céu da boca, com a ponta atrás dos dentes de cima, isso evitará que haja força errada nas estruturas operadas. {'\n'}{'\n'}Quando for engolir água ou saliva, comece a prestar atenção para a língua ficar também neste lugar. {'\n'}{'\n'}<Text style={styles.aviso2}>Depois da cirurgia passe a língua por dentro da boca para perceber a nova forma e ajudar na sensibilidade da região.</Text></Text>
      <Text style={styles.topico}>Com os lábios:</Text>
      <Text style={styles.texto}>Tente suavemente fazer biquinho e depois fazer sorriso, sem colocar força ou pressão, alterne entre o biquinho e o sorriso. {'\n'}Repita algumas vezes ao dia.
Para ajudar nos movimentos, fala e alimentação, procure um fonoaudiólogo.</Text>
      <Text style={styles.topico}>Umidificação dos lábios</Text>
      <Text style={styles.texto}>Os lábios podem ficar rachados e ressecados, isso ocorre pela manipulação durante a cirurgia. Procure hidratar os lábios com hidratante, manteiga de cacau, vaselina líquida ou pomada de assadura de nenê oleosa. Faça aplicações várias vezes ao dia.</Text>
      <Text style={styles.topico}>Exposição ao sol</Text>
      <Text style={styles.texto}>Evite o sol durante o pós-operatório, o calor pode aumentar o inchaço e se você tiver hematomas pode deixar a pele manchada. Procure usar filtro solar se tiver que ficar exposto ao sol ou a ambientes com luz fluorescente.</Text>
      <Text style={styles.topico}>Banho e curativos</Text>
      <Text style={styles.texto}>Você pode lavar o rosto normalmente, mas evite água quente, pois o calor aumenta o inchaço.</Text>
      <Text style={styles.topico}>Dor</Text>
      <Text style={styles.texto}>Em alguns casos o paciente vai para casa com um curativo de fita adesiva segurando o queixo, que será retirado no retorno ao médico após a cirurgia; mas você pode molhar e secar bem com toalha.

      {'\n'}{'\n'}Os pontos da cirurgia estão em sua gengiva sem curativos e o cuidado com este pontos é uma boa higiene oral após as refeições. Estes pontos são absorvidos pelo seu corpo conforme a cicatrização.</Text>
      <Text style={styles.topico}>Como dormir e respirar</Text>
      <Text style={styles.texto}>Ao deitar coloque 2 a 3 travesseiros para deixar a cabeça mais alta, isso facilita a respiração e a diminuir o inchaço.
Você pode sentir seu nariz entupido ou dolorido; isso ocorre porque o inchaço comprime muitas estruturas da face e a sensação dolorida pode ser do tubo colocado durante a cirurgia para você respirar (isso melhora dentro de alguns dias).</Text>
      <Text style={styles.topico}>Exercícios</Text>
      <Text style={styles.texto}>Para auxiliar a recuperação da cirurgia e da mobilidade e sensibilidade da região, você pode realizar alguns exercícios em casa após liberação do cirurgião.
Com a bochecha:
Coloque um pouco de ar dentro da boca e empurre o ar para lado direito e esquerdo dentro da boca, como se você fizesse uma bola na bochecha. Repita algumas vezes durante o dia.</Text>
      <Text style={styles.topico}>Repouso</Text>
      <Text style={styles.texto}>Toda a cirurgia exige nos primeiros dias um repouso; procure realizar poucas atividades durante este período.

      {'\n'}Sempre que estiver em repouso procure manter a cabeça mais alta que o corpo ou fique sentado e a cada 40 a 60 minutos movimente as pernas e os pés para melhorar a circulação. Procure caminhar a cada duas a três horas para manter boa circulação.

      {'\n'}{'\n'}<Text style={styles.aviso}>Evite levantar bruscamente. </Text>  {'\n'}{'\n'}Você poderá realizar atividades simples, como ficar no computador, ver filmes, jogar com amigos, ver televisão, ler, passear por períodos curtos, de preferência próximo a sua casa, para descansar após o passeio. {'\n'}{'\n'}</Text>
      
    </ScrollView>

   </SafeAreaView>
  );
}
const { height } = Dimensions.get('window')
const styles = StyleSheet.create({
  scroll:{
    width:'100%',
    height:'100%',
    alignContent: 'center',
    backgroundColor: '#242834'
  },
  topico:{
    color: '#9fa75a',
    fontFamily: 'PoppinsSemiBold',
    fontSize: 25,
    textAlign: 'center'
  },
  texto:{
    textAlign: 'justify',
    width: '90%',
    justifyContent: 'center',
    fontFamily: 'PoppinsRegular',
    left: '5%',
    color: '#ffffff'
  },
  aviso: {
    fontFamily: 'PoppinsSemiBold',
    color: '#c23234',
    left: '5%',
    textAlign: 'justify',
    width: '90%',
    justifyContent: 'center',
  },
  aviso2: {
    fontFamily: 'PoppinsSemiBold',
    color: '#efcc27',
    left: '5%',
    textAlign: 'justify',
    width: '90%',
    justifyContent: 'center',
  },
  tabela:{
    width: 383,
    height: 350,
    left: '3%'
  }
});













Cirurgia Ortognática





import React from 'react';
import { View, SafeAreaView, Text, Dimensions, Image, StyleSheet, ScrollView, ImageBackground, StatusBar } from 'react-native';
import { useNavigation } from '@react-navigation/native';


export default function Ortog() {
const navigation = useNavigation();  
 return (
   <SafeAreaView style={styles.container}><StatusBar backgroundColor={'#9fa75a'}/>
    <ImageBackground style={styles.img} source={require('../../../../assets/ImagemBase.jpg')} />

      <ScrollView style={styles.scroll}>
      
      <View style={styles.all}>
        <View style={styles.track}></View>
        <Text style={styles.h1}>O que é a cirurgia Ortognática?</Text>
        <Text style={styles.h2}>A Cirurgia Ortognática é o procedimento que visa corrigir anomalias dentofaciais. Essas alterações podem ser: de oclusão/mordida (mordida aberta, mordida cruzada), que não possam corrigidas apenas com tratamentos ortodônticos; assimetrias faciais; pouca projeção ou projeção excessiva do mento, da mandíbula e/ou da maxila; pouca altura ou altura excessiva do mento, da mandíbula e/ou da maxila.</Text>
        <Text style={styles.h3}>Nos pacientes com indicação para a realização desse tipo de cirurgia, as queixas são as mais diversas, desde falta de exposição dentária no sorriso, alterações no perfil por falta de projeção dos maxilares, dificuldade respiratória e para se alimentar, sorriso gengival, entre outras. A cirurgia visa corrigir alterações esqueléticas e está sempre associada ao tratamento ortodôntico, para que o produto final seja sempre o mais benéfico e satisfatório possível para o paciente. Temos ortodontistas em nossa equipe que já estão familiarizados e são experientes nos procedimentos pré, trans e pós-cirúrgicos.</Text>

      </View>
      <View style={{backgroundColor: '#242834'}}>
        <View style={styles.track2}></View>
        <View styles={styles.al2}>
          <Text style={styles.h12}>Pré-operatório</Text>
          <Text style={styles.h4}>Uma vez determinada a necessidade de realizar a Cirurgia Ortognática, o paciente deverá passar em várias consultas conosco, a fim de determinar o que será executado. Em nossa clínica desenvolvemos um planejamento minucioso para a realização da Cirurgia Ortognática. Trata-se de um protocolo em diversas etapas, que incluem desde simulações em 2D personalizadas, moldagens e fotos padronizadas até planejamentos em 3D, nos quais os pacientes podem analisar e discutir, junto com a nossa equipe, o resultado cirúrgico que deseja obter. O bom relacionamento entre o paciente, o cirurgião e a equipe é essencial para que todas as dúvidas sejam esclarecidas e para que haja confiança em todas as partes do tratamento.</Text>
          <Text style={styles.h4}>Como parte da preparação para a cirurgia, o paciente deve realizar exames pré-operatórios (Rx de tórax, Eletrocardiograma, Hemograma), que serão avaliados pelo cirurgião e pelo médico anestesista da equipe.</Text>

        </View>
        <View style={styles.track3}></View>
        <View styles={styles.al2}>
          <Text style={styles.tecnica}>Técnica cirúrgica</Text>
          <Text style={styles.tecnicah1}>Utilizamos uma Técnica Minimamente Invasiva que consiste em realizar acessos cirúrgicos menores, com o descolamento cuidadoso dos tecidos e uso de instrumentais específicos que promovem um trauma cirúrgico menor. Todos os acessos são realizados por dentro da boca, portanto, não há cicatrizes. Essas abordagens fazem com que os pacientes tenham pós-operatórios melhores, com menos inchaço, menores chances de parestesia e uma recuperação mais rápida.</Text>
        </View>
        <View style={styles.duraçaotrack}></View>
        <View styles={styles.al2}>
          <Text style={styles.duraçao}>Duração, Local e Anestesia</Text>
          <Text style={styles.duraçaoh1}>O procedimento cirúrgico tem duração de, aproximadamente, 5 (cinco) horas. é realizado em ambiente hospitalar sob anestesia geral e pode ser associado a diversos refinamentos estéticos, como a rinoplastia, a lipoaspiração submentual e a bichectomia. Todas as suturas (pontos) são absorvíveis. O paciente recebe alta no dia seguinte à cirurgia.</Text>
        </View>
        <View style={styles.postrack}></View>
        <View styles={styles.al2}>
          <Text style={styles.pos}>Pós operatório</Text>
          <Text style={styles.posh1}>Nas semanas iniciais de pós, além de tomar todos os medicamentos conforme prescritos, deve-se seguir uma alimentação pastosa e gelada. Com o acompanhamento, o paciente recebe, aos poucos, liberações para ir modificando e ampliando seu modo de se alimentar e ir retornando às suas atividades do dia a dia. Inchaço e edema são inerentes ao ato cirúrgico e vão reduzindo com o passar do tempo. Ações como as drenagens pós-operatórias, os cuidados com a pele e a aplicação de laser terapêutico são indicadas já nas primeiras semanas de pós, e há profissionais em nossa equipe que os realizam. A máscara Hilotherm também é um recurso bastante recomendado para os pacientes que passam pela cirurgia. Orientamos cada paciente no passo-a-passo, desde a solicitação cirúrgica realizada ao convênio até o momento no qual o paciente finaliza todo o seu tratamento.</Text>
        </View>
      </View>
      <Text> {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} </Text>
      <Text> {'\n'}  </Text>
    </ScrollView>

   </SafeAreaView>
  );
}
const { height } = Dimensions.get('window')
const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#242834',
    height: height,
  },
  scroll:{
    width: '100%',
    height: '100%',
    bottom: '0%',
    
    position: 'absolute',
  },
  img:{
    width: '100%',
    height: 210,
    position: 'relative',
  },
  all:{
    top: '5.5%',
    borderTopRightRadius: 21,
    borderTopLeftRadius: 21,
    backgroundColor: '#242834',
    width: '100%',
    alignItems:"center",
    height: 1150,
    position: 'relative',
  },
  al2:{
    top: 20,
    backgroundColor: '#242834',
    width: '100%',
    height: '100%',
    alignItems:"center",
    height: 900,
    position: 'relative',
  },
  track: {
    backgroundColor: '#9fa75a',
    width: '20%',

    top: '0.5%',
    height: '0.7%',
    borderRadius: 20,
  },
  track2: {
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '0.5%',
    height: '0.5%',
    borderRadius: 20,
  },
  track3: {
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '2%',
    height: '0.5%',
    borderRadius: 20,
  },
  h1: {
    color: '#FFF',
    fontSize: 20,
    color: '#9fa75a',
    top: '1.4%',
    fontFamily: "PoppinsSemiBold",
    backgroundColor: '#242834',
  },
  h12: {
    color: '#FFF',
    fontSize: 24,
    color: '#9fa75a',
    top: '1%',
    fontFamily: "PoppinsSemiBold",
    left: '27%',
  },

  h2: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '0%',
    width: '90%',
    top: '4%',
    fontFamily: "PoppinsRegular", 
  },
  h3: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '0%',
    width: '90%',
    top: '4%',
    fontFamily: "PoppinsRegular", 
  },
  h4:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '1%',
    fontFamily: "PoppinsRegular", 
  },
  tecnica: {
    fontSize: 24,
    color: '#9fa75a',
    top: '12%',
    fontFamily: "PoppinsSemiBold",
    left: '24%',
  },
  tecnicah1: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '14%',
    fontFamily: "PoppinsRegular", 
  },
  h5:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '1%',
    fontFamily: "PoppinsRegular", 
  },
  duraçao:{
    fontSize: 22,
    color: '#9fa75a',
    top: '23%',
    fontFamily: "PoppinsSemiBold",
    left: '12%',
  },
  duraçaotrack:{
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '3.2%',
    height: '0.5%',
    borderRadius: 20,
  },
  duraçaoh1:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '25%',
    fontFamily: "PoppinsRegular", 
  },
  pos:{
    fontSize: 24,
    color: '#9fa75a',
    top: '9.5%',
    fontFamily: "PoppinsSemiBold",
    left: '27%',
  },
  postrack:{
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '3%',
    height: '0.5%',
    borderRadius: 20,
  },
  posh1:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '10%',
    fontFamily: "PoppinsRegular", 
  }
});








Siso Incluso




import React from 'react';
import { View, SafeAreaView, Text, Dimensions, Image, StyleSheet, ScrollView, ImageBackground, StatusBar } from 'react-native';
import { useNavigation } from '@react-navigation/native';


export default function Ortog() {
const navigation = useNavigation();  
 return (
   <SafeAreaView style={styles.container}><StatusBar backgroundColor={'#9fa75a'}/>
    <ImageBackground style={styles.img} source={require('../../../../assets/ImagemBase.jpg')} />

      <ScrollView style={styles.scroll}>
      
      <View style={styles.all}>
        <View style={styles.track}></View>
        <Text style={styles.h1}>O que é o Dente Incluso ou   Impactado??</Text>
        <Text style={styles.h2}>Dente incluso ou impactado é aquele elemento dentário que, apesar de totalmente desenvolvido, não conseguiu erupcionar no período adequado. Dentes não erupcionam principalmente devido à falta de espaço na arcada dentária. Os principais dentes impactados são os terceiros molares (sisos), caninos superiores e pré-molares inferiores.</Text>
        <Text style={styles.h3}>Os terceiros molares (sisos) são os principais dentes inclusos por serem os últimos dentes a erupcionarem e por não terem espaço na arcada dentária. Como regra geral, baseando-se nos princípios da odontologia preventiva, todos os dentes impactados devem ser removidos antes que haja complicações, a menos que, por motivo maior, a remoção esteja contra indicada. A remoção dos dentes impactados torna-se mais difícil com o avanço da idade. </Text>

      </View>
      <View style={{backgroundColor: '#242834'}}>
        <View style={styles.track2}></View>
        <View styles={styles.al2}>
          <Text style={styles.h12}>Pré-operatório</Text>
          <Text style={styles.h4}>Para que a extração seja realizada é necessário que o paciente realize exames de imagem, como uma radiografia panorâmica, para que nervos e estruturas adjacentes sejam localizados e preservados.</Text>
        </View>
        <View style={styles.track3}></View>
        <View styles={styles.al2}>
          <Text style={styles.tecnica}>Técnica cirúrgica</Text>
          <Text style={styles.tecnicah1}>Dentre as técnicas utilizadas está a sedação por via oral com o uso de medicamentos ansiolíticos que visam a redução do stress, pressão arterial e frequência cardíaca. Além da sedação, utilizamos medicamentos antibióticos, antiinflamatórios e analgésicos que visam eliminar os riscos de infecção, inflamação e dor pós operatória.</Text>
        </View>
        <View style={styles.duraçaotrack}></View>
        <View styles={styles.al2}>
          <Text style={styles.duraçao}>Cirurgia</Text>
          <Text style={styles.duraçaoh1}>A cirurgia pode ter duração entre 60 e 90 minutos, dependendo da complexidade e da quantidade de dentes a serem removidos. É realizada com auxílio de equipamentos modernos, anestesia com drogas anestésicas de longa duração e com técnicas operatórias precisas, onde o trauma cirúrgico é o menor possível e a recuperação pós operatória é bastante tranquila.</Text>
        </View>
      </View>
      <Text> {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} {'\n'} </Text>
      <Text> {'\n'}  </Text>
    </ScrollView>

   </SafeAreaView>
  );
}
const { height } = Dimensions.get('window')
const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#242834',
    height: height,
  },
  scroll:{
    width: '100%',
    height: '100%',
    bottom: '0%',
    
    position: 'absolute',
  },
  img:{
    width: '100%',
    height: 210,
    position: 'relative',
  },
  all:{
    top: '8.5%',
    borderTopRightRadius: 21,
    borderTopLeftRadius: 21,
    backgroundColor: '#242834',
    width: '100%',
    alignItems:"center",
    height: 1150,
    position: 'relative',
  },
  al2:{
    top: 20,
    backgroundColor: '#242834',
    width: '100%',
    height: '100%',
    alignItems:"center",
    height: 900,
    position: 'relative',
  },
  track: {
    backgroundColor: '#9fa75a',
    width: '20%',

    top: '0.5%',
    height: '0.4%',
    borderRadius: 20,
  },
  track2: {
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '0.5%',
    height: '0.5%',
    borderRadius: 20,
  },
  track3: {
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '4%',
    height: '0.5%',
    borderRadius: 20,
  },
  h1: {
    color: '#FFF',
    fontSize: 23,
    color: '#9fa75a',
    top: '1.4%',
    fontFamily: "PoppinsSemiBold",
    backgroundColor: '#242834',
  },
  h12: {
    color: '#FFF',
    fontSize: 24,
    color: '#9fa75a',
    top: '1%',
    fontFamily: "PoppinsSemiBold",
    left: '27%',
  },

  h2: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '0%',
    width: '90%',
    top: '4%',
    fontFamily: "PoppinsRegular", 
  },
  h3: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '0%',
    width: '90%',
    top: '4%',
    fontFamily: "PoppinsRegular", 
  },
  h4:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '1%',
    fontFamily: "PoppinsRegular", 
  },
  tecnica: {
    fontSize: 24,
    color: '#9fa75a',
    top: '12%',
    fontFamily: "PoppinsSemiBold",
    left: '24%',
  },
  tecnicah1: {
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '14%',
    fontFamily: "PoppinsRegular", 
  },
  h5:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '1%',
    fontFamily: "PoppinsRegular", 
  },
  duraçao:{
    fontSize: 24,
    color: '#9fa75a',
    top: '23%',
    fontFamily: "PoppinsSemiBold",
    left: '37%',
  },
  duraçaotrack:{
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '8.5%',
    height: '0.5%',
    borderRadius: 20,
  },
  duraçaoh1:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '25%',
    fontFamily: "PoppinsRegular", 
  },
  pos:{
    fontSize: 24,
    color: '#9fa75a',
    top: '9.5%',
    fontFamily: "PoppinsSemiBold",
    left: '27%',
  },
  postrack:{
    backgroundColor: '#9fa75a',
    width: '20%',
    left: '40%',
    top: '3%',
    height: '0.5%',
    borderRadius: 20,
  },
  posh1:{
    color: '#FFF',
    textAlign: 'justify',
    fontSize: 17,
    left: '5%',
    width: '90%',
    top: '10%',
    fontFamily: "PoppinsRegular", 
  }
});



Higiene Oral
Dieta
Abertura da boca
Cuidados
dor
Repouso