> [!ccs]
> Заметки по сss
<h2 style="color: #007AFF">Font weight</h2>
<ul>
  <li><strong>100</strong> - Thin (Hairline)</li>
  <li><strong>200</strong> - Extra Light (Ultra Light)</li>
  <li><strong>300</strong> - Light</li>
  <li><strong>400</strong> - Regular (Normal)</li>
  <li><strong>500</strong> - Medium</li>
  <li><strong>600</strong> - Semi Bold (Demi Bold)</li>
  <li><strong>700</strong> - Bold</li>
  <li><strong>800</strong> - Extra Bold (Ultra Bold)</li>
  <li><strong>900</strong> - Black (Heavy)</li>
</ul>
<h2 style="color: #007AFF">will-change: transform;</h2>
<p>Свойство для использования при трансформе</p>
<h2 style="color: #007AFF">Cвойства для переноса через - </h2>
<ul>
  <li>hyphens: auto;</li>
  <li>-moz-hyphens: auto;</li>
  <li>-webkit-hyphens: auto;</li>
  <li>-ms-hyphens: auto;</li>
</ul>
<h2>
  Animation
</h2>
<p>
  animation: animationGradient 10s linear forwards infinite;
  <a href="https://doka.guide/css/animation-iteration-count/">link</a>
</p>

<h2>
  Cкрыть текст точками 
</h2>

   overflow: hidden;<br>
	text-overflow: ellipsis;<br>
	display: -webkit-box;<br>
	-webkit-line-clamp: 4;<br>
	-webkit-box-orient: vertical;<br>

<h2>transition</h2>
<h3>transition: [transition-property] [transition-duration] [transition-timing-function] [transition-delay];</h3>
<ul>
	<li>
		transition-property Определяет, какие свойства будут анимированы
	</li>
	<li>
		transition-duration Определяет продолжительность анимации.
	</li>
	<li>
		transition-timing-function Определяет скорость изменения анимируемого свойства.
	</li>
	<li>
		transition-delay Определяет задержку перед началом анимации.
	</li>
</ul>
<h2>Растянуть слайды swiper</h2>
<p>
	Для .swiper-wrapper устанавливаете align-items: stretch;, а для .swiper-slide height: auto; - в таком случае .swiper-slide будет растягиватся по высоте самого высокого слайда.
</p>
