---
layout: page
lang: pt
title: Contato
permalink: /pt/contato/
alt_lang: /en/contact/
---

<section class="page-shell">
	<h1>Contato</h1>

	<div class="contact-layout">
		<div class="contact-text">
			<h2>Fale com o LAM+</h2>
			<p>O LAM+ recebe demandas relacionadas à análise, imageamento e caracterização de amostras sedimentares e materiais associados, com foco em técnicas de alta resolução, abordagens não destrutivas e integração entre dados espectrais, geoquímicos, físicos e computacionais. O laboratório também atua no desenvolvimento de soluções baseadas em inteligência artificial para apoiar a interpretação de sequências sedimentares, identificação de padrões, integração de dados multiproxy e construção de fluxos analíticos mais reprodutíveis.</p>

			<p>Entre em contato conosco para discutir o envio ou avaliação prévia de amostras, a capacidade técnica dos equipamentos disponíveis, possibilidades de análises em testemunhos sedimentares, seções ou amostras discretas, além de parcerias científicas, interinstitucionais ou tecnológicas.</p>

			<p>Cada demanda será avaliada considerando o tipo de material, o estado de preservação da amostra, os objetivos científicos ou técnicos do estudo, a disponibilidade operacional dos equipamentos e a eventual necessidade de desenvolvimento metodológico específico.</p>

			<p>O LAM+ atua como uma plataforma multiusuária voltada à inovação em geociências, combinando imageamento hiperespectral, XRF core scanning, radiografia sedimentar, MEV-EDS e inteligência artificial aplicada a sequências sedimentares.</p>
		</div>
		<div class="contact-image">
			<img src="{{ site.baseurl }}/assets/img/hero/hero-combo-contact.png" alt="LAM+ contact" />
		</div>
	</div>
</section>

<style>
.contact-layout {
	display: flex;
	gap: 2rem;
	align-items: flex-start;
}
.contact-text {
	flex: 1 1 0;
	min-width: 0;
}
.contact-image {
	flex: 0 0 auto;
	display: flex;
	align-items: flex-start;
	padding-top: 0.25rem;
}
.contact-image img {
	width: 220px;
	max-width: 100%;
	height: auto;
	display: block;
	border-radius: 6px;
}
@media (max-width: 640px) {
	.contact-layout {
		flex-direction: column;
	}
	.contact-image img {
		width: 100%;
		max-width: 320px;
	}
}
</style>
