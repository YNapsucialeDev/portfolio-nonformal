<template>
<div>
	<div class="intro" id="video">
		<h1>Yannick Napsuciale Software Developer</h1>
		<video id="videofile" src="@/assets/vid2.mp4"></video>
	</div>
	<div id="pinContainer">
		<section id="frontend">
			<img class="technologies" src="@/assets/frontend.svg" alt="frontend">	
			<br>
			<br>
			<h1 class="bold">Tecnologías FrontEnd</h1>
		</section>
		<section id="angular" class="bold">
			<img class="technologies" src="@/assets/angular.png" alt="angular">	
			<br>
			<br>
			<p class="text-justify">
				Framework para los peresozos que no quieren diseñar una nueva estructura de código para trabajar en equipo.
			</p>
			<p class="text-justify">
				Para poder ser hipster y decir que usas TypeScript, además de tener playeras muy chidas.
			</p>
			<ul>
				<li>Plataformas Administrativas</li>
				<li>Dashboard</li>
				<li>Ecommerce</li>
				<li>Páginas web</li>
				<li>Experiencias digitales</li>
				<li>Esencialmente todo lo que se pueda hacer FrontEnd en la Web</li>
			</ul>
		</section>
		<section id="vue" class="bold">
			<img class="technologies" src="@/assets/vue.png" alt="vue">	
			<br>
			<br>
			<p class="text-justify">
				Framework para los peresozos que no quieren aprender Angular, pero son demasiado hipsters para aprender React.
			</p>
			<p class="text-justify">
				El framework esta chido para hacer proyecto solo, rápido, donde no te importe seguir directrices estructurales para trabajar en equipo, AKA: "El Framework de los fines de semana"
			</p>
			<ul>
				<li>Plataformas Administrativas</li>
				<li>Dashboard</li>
				<li>Ecommerce</li>
				<li>Páginas web</li>
				<li>Experiencias digitales</li>
				<li>Esencialmente todo lo que se pueda hacer FrontEnd en la Web</li>
			</ul>
		</section>
		<section id="bootstrap" class="bold">
			<img class="technologies" src="@/assets/bootstrap.png" alt="bootstrap">	
			<br>
			<br>
			<p class="text-justify">
				¿Bootstrap?... Ni siquiera lo voy a mencionar, ya es tan básico como Microsoft Office.
			</p>
			<img class="tecnologies" src="@/assets/tona-skill.png" alt="tona-basic-skill">
		</section>
		<section id="material" class="bold">
			<img class="technologies" src="@/assets/angular-material.png" alt="material">	
			<br>
			<br>
			<p class="text-justify">
				Angular Material me ha sacado de tantos apuros que ya es mi "go to" UI Toolkit, además que Material Design es una cosa preciosa.
			</p>
		</section>
		
	</div>
	<div id="backendContainer">
		<div id="sliderContainer">
			<section id="backend">
				<img class="technologies" src="@/assets/backend.png" alt="backend">	
				<br>
				<br>
				<h1 class="bold">Tecnologías Backend</h1>
			</section>
			<section id="codeigniter" class="bold">
				<img class="technologies" src="@/assets/codeigniter.png" alt="codeigniter">	
				<img class="technologies" src="@/assets/php.png" alt="php">	
				<br>
				<br>
				<p class="text-justify">
					Como todo profesional, PHP es el tooling que debes de saber, sí o sí, aunque lo odies con toda la extensión de tu alma.
				</p>
				<p class="text-justify">
					¿Pero por qué?... ¿Tienes clientes que no quieren invertir en buena infraestructura?, éste es tu producto.
					¿La página de tus clientes fue creada antes de 1999? Seguro es PHP.
					¿El anterior proveedor no era desarrollador y usaba un CMS? Seguro es PHP.
					¿Amas la frustración y prefieres no tocar tecnologías buenas porque son hipsters? <strong>SEGURO ERES PHP</strong>
				</p>
				<p style="font-size: 75%">Las opiniones escritas en esta página, SI reflejan sus propias opiniones. Aprendar Javascript por favor...</p>
			</section>
			<section id="express" class="bold">
				<img class="technologies" src="@/assets/node.png" alt="node">	
				<br>
				<img class="technologies" src="@/assets/express.png" alt="express">	
				<br>
				<br>
				<p class="text-justify">
					Severamente desactualizado, pero increíblemente poderoso y fácil de usar, ya sea prototipado o bomberazo, el framework ligero de mi elección
				</p>
				<p class="text-justify">
					No te pongas hipster, Express es el chido cuando necesitas hacer algo rápido y consistente (bueno, depende de tu código), pero no te preocupes que enseguida subimos
					el nivel de "hipteres";
				</p>
			</section>
			<section id="nest" class="bold">
				<img class="technologies" src="@/assets/nest.png" alt="nest">	
				<br>
				<br>
				<p class="text-justify">
					NestJS, el hijo favorito de Express y Koa, framework increíble si vienes de Angular, TypeScript... Gracias.
				</p>
				<p class="text-justify">
					¿Routing? ¿Seguridad? ¿Autenticación? ¿Parsing? ¿Team Express? ¿Team Koa?, ¿Bundling? Este lo tiene todo, si eres lo suficientemente hipster y tu barba esta larga.
				</p>
			</section>
			<section id="golang" class="bold">
				<img class="technologies" src="@/assets/golang.png" alt="golang">	
				<br>
				<br>
				<p class="text-justify">
					¿Se puede ser mas hipster en esta industria?
				</p>
				<p class="text-justify">
					Pero claro, ¡siempre se puede mas! Con este lenguaje derivado de poner a tener hijos a javascript/python/coffescript en la fiesta mas divertida de la historia.
					Se puede hacer todo un backend completo con un rendimiento sin igual, puedes checar Gin, Martini o Echo(mi favorito), pero ten cuidado, el manejo de dependencias puede ser un 
					dolor de cabeza si estas acostumbrado (de mala manera) al desorden que es npm.
				</p>
			</section>
		</div>
	</div>
	<section id="buscasmas">
		<p class="text-justify">
			¿Todavía buscas mas de mi? Pues vamos a ver...
		</p>
		<img class="tecnologies" src="@/assets/tona-skill.png" alt="tona-basic-skill">
	</section>
	<div id="databaseContainer">
		<section id="mysql" class="bold">
			<img class="tecnologies" src="@/assets/mysql.png" alt="mysql">
			<br>
			<p class="text-justify">
				MySQL, ¡Porque si fui a la universidad!
			</p>
			<img class="tecnologies" src="@/assets/tona-skill.png" alt="tona-basic-skill">
		</section>
		<section id="postgres" class="bold">
			<img class="tecnologies" src="@/assets/postgres.png" alt="postgres">
			<br>
			<p class="text-justify">
				PostgreSQL, porque queriamos formatos fáciles de manejar sin límites.
			</p>
		</section>
		<section id="mongo" class="bold">
			<img class="tecnologies" src="@/assets/mongo.png" alt="mongo">
			<br>
			<p class="text-justify">
				Porque por alguna razón a los hipters mas hipsters les encanta.
			</p>
		</section>
	</div>
	<section id="extras" class="bold">
		<p class="text-justify" style="font-size: 200%">
			EXTRAS
		</p>
	</section>
	<div id="extrasContainer">
		<section id="docker" class="bold">
			<img class="tecnologies" src="@/assets/docker.png" alt="docker">
			<br>
			<p class="text-justify">
				Para este punto ya estoy cansado con esta página eterna, pero esta herramienta cambio la manera en la que hago las cosas.
			</p>
			<ul>
				<li>Versiones de producción</li>
				<li>Environment Control</li>
				<li>Actualizaciónes sin down-time</li>
				<li>Esta cool</li>
			</ul>
		</section>
		<section id="git" class="bold">
			<img class="tecnologies" src="@/assets/git.png" alt="git">
			<br>
			<p class="text-justify">
				Esenciales, como saber usar Google Chrome, sin esto no trabajas.
			</p>
		</section>
		<section id="hasura" class="bold">
			<img class="tecnologies" src="@/assets/hasura.png" alt="hasura">
			<br>
			<p class="text-justify">
				La herramienta mas cool para prototipado rápido y control de accesos al mínimo nivel, excelente proyecto.
			</p>
		</section>
		<section id="strapi" class="bold">
			<img class="tecnologies" src="@/assets/strapi.png" alt="strapi">
			<br>
			<p class="text-justify">
				Headless CMS de preferencia, si llegaste a este punto es porque te interesa el tema, #fistBump my man.
			</p>
		</section>
	</div>
</div>
</template>

<script>
export default {
	name: "Home",
	components: {},
	mounted() {
		/**
		 * VIDEO ANIMATION SECTION
		 */
		const video = document.getElementById('videofile');
		const controller = new ScrollMagic.Controller();
		let scene = new ScrollMagic.Scene({
			duration: 12000,
			triggerElement: '#video',
			triggerHook: 'onLeave'
		})
		.addTo(controller)
		.setPin('#video');

		//video animation
		let accelamount = 0.05;
		let scrollpos = 0;
		let delay = 0;

		scene.on('update', (event) => {
			scrollpos = event.scrollPos / 1000; //to handle seconds instead of millis
		});

		setInterval(() => {
			delay += (scrollpos - delay) * accelamount;
			video.currentTime = delay;
		}, 60);

		/**
		 * VIDEO ANIMATION SECTION END
		 */

		/**
		 * FRONTEND SECTION
		 */

		let techTween = new TimelineMax()
			.fromTo("#angular", 1, {x: "-100%"}, {x: "0%", ease: Linear.easeNone})
			.fromTo("#vue",    1, {x:  "100%"}, {x: "0%", ease: Linear.easeNone})
			.fromTo("#bootstrap",    1, {y:  "-100%"}, {y: "0%", ease: Linear.easeNone})
			.fromTo("#material",    1, {y:  "100%"}, {y: "0%", ease: Linear.easeNone})
			.kill();

		new ScrollMagic.Scene({
			duration: 10000,
			triggerElement: '#pinContainer',
			triggerHook: 'onLeave'
		})
		.setPin('#pinContainer')
		.setTween(techTween)
		.addTo(controller);

		/**
		 * FRONTEND SECTION FIN
		 */

		/**
		 * BACKEND SECTION
		 */

		let backendTween = new TimelineMax()
			.to("#sliderContainer", 1,   {x: "-20%"})
			.to("#sliderContainer", 1,   {x: "-40%"})
			.to("#sliderContainer", 1,   {x: "-60%"})
			.to("#sliderContainer", 1,   {x: "-80%"})
			.kill();

		new ScrollMagic.Scene({
			duration: '500%',
			triggerElement: '#backendContainer',
			triggerHook: 'onLeave'
		})
		.setPin('#backendContainer')
		.setTween(backendTween)
		.addTo(controller);

		/**
		 * BACKEND SECTION END
		 */


		/**
		 * DATABASES SECTION 
		 */

		
		let dbTween = new TimelineMax()
			.fromTo("#mysql", 1, {y:  "-100%", x: '-100%'}, {y: "0%", x: '0%',  ease: Linear.easeNone})
			.fromTo("#postgres",    1, {y:  "100%", x: '100%'}, {y: "0%", x: '0%',  ease: Linear.easeNone})
			.fromTo("#mongo",    1, {y:  "-100%", x: '-100%'}, {y: "0%", x: '0%',  ease: Linear.easeNone})
			.kill();

		new ScrollMagic.Scene({
			duration: 10000,
			triggerElement: '#databaseContainer',
			triggerHook: 'onLeave'
		})
		.setPin('#databaseContainer')
		.setTween(dbTween)
		.addTo(controller);

		/**
		 * EXTRAS SECTION 
		 */

		
		let extrasTween = new TimelineMax()
			.fromTo("#git", 1, {x: '-100%', opacity:0.3, scale: 0, borderRadius: '100%'}, {x: '0%', opacity:1, scale: 1, borderRadius: '0%', ease: Linear.easeOut })
			.fromTo("#hasura",    1, {x: '100%', opacity:0.3, scale: 0, borderRadius: '100%'}, {x: '0%', opacity:1, scale: 1, borderRadius: '0%', ease: Linear.easeOut })
			.fromTo("#strapi",    1, {x: '-100%', opacity:0.3, scale: 0, borderRadius: '100%'}, {x: '0%', opacity:1, scale: 1, borderRadius: '0%', ease: Linear.easeOut })
			.kill();

		new ScrollMagic.Scene({
			duration: 8000,
			triggerElement: '#extrasContainer',
			triggerHook: 'onLeave'
		})
		.setPin('#extrasContainer')
		.setTween(extrasTween)
		.addTo(controller);
		
		controller.kill();
	}
};
</script>

<style lang="scss">
	.bold {
		font-weight: bold;
	}

	.intro {
		height: 100vh;
	}

	.intro video {
		height: 100%;
		width: 100%;
		object-fit: cover;
	}

	.intro h1 {
		position: absolute;
		top: 50%;
		left: 50%;
		transform: translate(-50%, -50%);
		color: white;
		font-size: 60px;    
		text-align: center;
	}

	#pinContainer {
		width: 100%;
		height: 100vh;
		overflow: hidden;
	}

	#pinContainer section {
		padding: 15%;
		height: 100%;
		width: 100%;
		display: flex!important;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		position: absolute;
	}

	#frontend {
		background: rgba(143, 248, 190, 0.953);
	}

	#angular {
		background: rgb(242, 171, 171);
	}

	#vue {
		background: rgb(175, 255, 198);
	}

	#bootstrap {
		background: rgb(197, 176, 255);
	}

	#material {
		background: rgb(176, 198, 255);
	}

	#backendContainer {
		width: 100%;
		height: 100vh;
		overflow: hidden;
		perspective: 1000;
	}

	#sliderContainer {
		width: percentage(5);
    	height: 100%;
	}

	#backendContainer section {
		padding: 1%;
		height: 100%;
		width: calc( 100% / 5 );
		display: flex!important;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		float: left;
		position: relative;
	}

	#backend {
		background: rgb(0, 0, 0);
		color: white;
	}

	#codeigniter {
		background: rgb(255, 204, 177);
		width: 100%;
	}

	#express {
		background: rgb(226, 226, 226);
		width: 100%;
	}

	#nest {
		background: rgb(0, 0, 0);
		color: white;
		width: 100%;
	}

	#golang {
		background: rgb(214, 226, 255);
		width: 100%;
	}

	.technologies {
		width: 30%;
	}

	#buscasmas {
		padding: 15%;
		height: 100%;
		width: 100%;
		display: flex!important;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		position: absolute;
		background: rgb(226, 226, 226);
	}

	#extras {
		padding: 15%;
		height: 100%;
		width: 100%;
		display: flex!important;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		position: absolute;
		background: rgb(226, 226, 226);
	}

	#databaseContainer {
		width: 100%;
		height: 100vh;
		overflow: hidden;
	}

	#databaseContainer section {
		padding: 15%;
		height: 100%;
		width: 100%;
		display: flex!important;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		position: absolute;

		img {
			width: 40%;
		}
	}

	#mysql {
		background: rgb(197, 176, 255);
	}

	#postgres {
		background: rgb(68, 77, 175);
		color: white;
	}

	#mongo {
		background: rgb(94, 196, 135);
	}

	//-------------------------

	#extrasContainer {
		width: 100%;
		height: 100vh;
		overflow: hidden;
	}

	#extrasContainer section {
		padding: 15%;
		height: 100%;
		width: 100%;
		display: flex!important;
		justify-content: center;
		align-items: center;
		flex-direction: column;
		position: absolute;

		img {
			width: 40%;
		}
	}

	#docker {
		background: rgb(141, 170, 243);
	}

	#hasura {
		background: rgb(178, 245, 184);
	}

	#strapi {
		background: rgb(164, 201, 255);
	}

	#git {
		background: rgb(245, 194, 139);
	}
</style>
