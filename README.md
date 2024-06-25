<!DOCTYPE html>
<html lang="fr"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Booki</title>
    
    
    
    
    
<style type="text/css" id="operaUserStyle"></style><style type="text/css"></style><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin=""><link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;500;700&amp;display=swap&amp;_cacheOverride=1698070490697" rel="stylesheet"><link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css?_cacheOverride=1698070490697"><link rel="stylesheet" href="http://127.0.0.1:5501/css/style.css?_cacheOverride=1698070490697"><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin=""><link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700;900&amp;display=swap&amp;_cacheOverride=1698070490698" class="wtd-font"><link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Unbounded&amp;_cacheOverride=1698070490698" class="wtd-font"></head>

<body>
    <div class="main-container">
        <div class="container">
            <header>
                <div class="header-left">
                <img src="images/logo/Booki.png" alt="Logo de Booki" class="button-icon">
                </div>
                <div class="header-right">
                    <a href="#section-title">Hébergements</a>
                    <a href="#activitep">Activités</a>
                </div>
            </header>

        </div>
        <div class="nature">
            <h2>Trouvez votre hébergement pour des vacances de rêve</h2>
            <p>En plein centre-ville ou en pleine nature</p>
        </div>
        <div class="search-container">
            <img src="images/logo/Vector.svg" alt="LogoVector" class="logo-container">

            <input type="text" id="ville" name="ville" placeholder="Marseille, France" required="" class="search-input">
            <button type="submit" class="search-button"></button>
        </div>


        <div class="Filtre">
            <h2> Filtres</h2>
            <div class="button-container">

                <button class="filter-button" title="logoéco">
                    <img src="images/logo/Property1=price.svg" alt="price" class="button-icon">
                    Économique
                </button>
                    <button class="filter-button" title="Logo famille">
                        <img src="images/logo/Property1=family.svg" alt="family" class="button-icon">
                        Famillial
                    </button>
                    <button class="filter-button" title="logoromantic">
                        <img src="images/logo/Property1=romantic.svg" alt="romantic" class="button-icon">
                        Romantique
                    </button>
                    <button class="filter-button" title="logofire">
                        <img src="images/logo/Property1=fire.svg" alt="fire" class="button-icon">
                        Nos pépites
                    </button>
            </div>

            <div class="info-container">
                <button class="svg-button" title="logoinfo" id="afficherMessage1">
                    <img src="images/logo/Property1=info.svg" class="button-icon" alt="Icône de info">

                </button>
                <h5 class="villelogements">Plus de 500 logements sont disponibles dans cette ville</h5>
            </div>
        </div>
        <main>
            <div class="hebergements-and-populaires">
                <section class="hebergements">
                    <div class="hebergements-title">  
                        <h2 id="section-title">Hébergements à Marseille</h2>
                     
                        
                           
                                <div class="hebergements-card">
                                        <article class="card">
                                            <a href="#">
                                            <img src="./images/hebergements/fred-kleber.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                            <div class="card-content">
                                                <div class="card-txt">
                                                    <h3 class="card-title">Hôtel du port</h3>
                                                    <p class="card-subtitle">Nuit à partir de 71<span class="euro">€</span></p>
                                                <div class="card-rating">
                                                    <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                    <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                    <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                    <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                    <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                                    <span class="sr-only">Note de 4 sur 5</span>
                                               </div>   
                                               </div>       
                                            </div> 
                                        </a>                                    
                                   
                                        </article>
                                    
                               
                                        <article class="card">
                                            <a href="#">
                                                <img src="./images/hebergements/febrian-zakaria.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                                <div class="card-content">
                                                    <div class="card-txt">
                                                        <h3 class="card-title">Hôtel chez Amina</h3>
                                                        <p class="card-subtitle">Nuit à partir de 96<span class="euro">€</span></p>
                                                        <div class="card-rating">
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                                            <span class="sr-only">Note de 4 sur 5</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </a> <!-- Fermez la balise <a> ici -->
                                        </article>

                                        <article class="card">
                                            <a href="#">
                                                <img src="./images/hebergements/reisetopia.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                                <div class="card-content">
                                                    <div class="card-txt">
                                                        <h3 class="card-title">Hôtel Les Mouettes</h3>
                                                        <p class="card-subtitle">Nuit à partir de 76<span class="euro">€</span></p>
                                                        <div class="card-rating">
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                                            <span class="sr-only">Note de 4 sur 5</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            
                                        </a> <!-- Fermez la balise <a> ici -->
                                        </article>
                                        </div>
                                         
                                        <div class="hebergements-card">
                                        <article class="card">
                                            <a href="#">
                                                <img src="./images/hebergements/annie-spratt.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                                <div class="card-content">
                                                    <div class="card-txt">
                                                        <h3 class="card-title">Hôtel de la Mer</h3>
                                                        <p class="card-subtitle">Nuit à partir de 46<span class="euro">€</span></p>
                                                        <div class="card-rating">
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                                            <span class="sr-only">Note de 4 sur 5</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            
                                            </a> <!-- Fermez la balise <a> ici -->
                                        </article>
                                                 
                            
                                        <article class="card">
                                            <a href="#">
                                                <img src="./images/hebergements/marcus-loke.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                                <div class="card-content">
                                                    <div class="card-txt">
                                                        <h3 class="card-title">Auberge La Canebière</h3>
                                                        <p class="card-subtitle">Nuit à partir de 25<span class="euro">€</span></p>
                                                        <div class="card-rating">
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                                            <span class="sr-only">Note de 4 sur 5</span>
                                                        </div>
                                                    </div>
                                                </div>
                                            </a> <!-- Fermez la balise <a> ici -->
                                        </article>
                                        
                                        
                                        <article class="card">
                                            <a href="#">
                                                <img src="./images/hebergements/nicate-lee.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                                <div class="card-content">
                                                    <div class="card-txt">
                                                        <h3 class="card-title">Auberge Le Panier</h3>
                                                        <p class="card-subtitle">Nuit à partir de 23<span class="euro">€</span></p>
                                                        <div class="card-rating">
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                            <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                                            <span class="sr-only">Note de 4 sur 5</span>
                                                        </div>
                                                    </div>
                                                </div>
                                
                                            </a> <!-- Fermez la balise <a> ici -->
                                        </article>                                           
                                     </div>
                       </div>

                            <div class="afficher-plus">
                        <a href="#">Afficher plus</a>
                        </div>
                        
                  
                    
                </section>
               
                <section class="populaires">
                    <div class="populaires-title">
                        <a href="#" class="section-link">
                            <h2 class="section-title">
                                Les plus populaires
                                <i class="fa-solid fa-chart-line" aria-hidden="true"></i>
                            </h2>

                        </a>
                    </div>
                 <div class="populaires-card">
                        <a href="#">
                            <article class="card">
                                <img src="./images/hebergements/emile-guillemot.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                <div class="card-content">
                                    <div class="card-txt">
                                        <h3 class="card-title">Hôtel Le soleil du matin</h3>
                                        <p class="card-subtitle">Nuit à partir de 128<span class="euro">€</span></p>
                                    <div class="card-rating">
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <span class="sr-only">Note de 5 sur 5</span>
                                    </div>
                                </div>
                         </div>
                            </article>
                            </a>
                            <a href="#">
                            <article class="card">
                                <img src="./images/hebergements/aw-creative.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                <div class="card-content">
                                    <div class="card-txt">
                                        <h3 class="card-title">Chambre d'hôtes Au coeur de l'eau</h3>
                                        <p class="card-subtitle">Nuit à partir de 71<span class="euro">€</span></p>
                                    
                                    <div class="card-rating">
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                        <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                        <span class="sr-only">Note de 4 sur 5</span>
                                    </div>
                                </div>
                                </div>
                                
                            </article>
                            </a>
                            <a href="#">
                                <article class="card">
                                    <img src="./images/hebergements/febrian-zakaria2.jpg" alt="Image de la chambre d'hôtel montrant un lit">
                                    <div class="card-content">
                                        <div class="card-txt">
                                            <h3 class="card-title">Hôtel Bleu et blanc</h3>
                                            <p class="card-subtitle">Nuit à partir de 68<span class="euro">€</span></p>
                                            <div class="card-rating">
                                                <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                <i class="fa-xs fa-solid fa-star" aria-hidden="true"></i>
                                                <i class="fa-xs fa-solid fa-star neutral-star" aria-hidden="true"></i>
                                                <span class="sr-only">Note de 4 sur 5</span>
                                            </div>
                                        </div>
                                    </div>
                                </article>
                            </a>
                        </div>  
              
               </section>
            </div>
        </main>

        <section id="activitep">
            <h2 class="section-title">Activités à Marseille</h2>
            <div class="activites-card">
                <article class="card activite-card">
                    <a href="#">
                    <img class="activite-image" src="./images/activites/reno-laithienne.jpg" alt="Image du Vieux-Port">
                    <div class="card-content">
                        <div class="card-txt">
                            <h3 class="card-title">Vieux-Port</h3>
                        </div>
                    </div>
                    </a>
                </article>
                <article class="card activite-card">
                    <a href="#">
                    <img class="activite-image" src="./images/activites/paul-hermann.jpg" alt="Image du Vieux-Port">
                    <div class="card-content">
                        <div class="card-txt">
                            <h3 class="card-title">Fort de Pomègues</h3>
                        </div>
                    </div>
                </a>
                </article>

                <article class="card activite-card">
                    <a href="#">
                    <img class="activite-image" src="./images/activites/kilyan-sockalingum.jpg" alt="Image du Vieux-Port">
                    <div class="card-content">
                        <div class="card-txt">
                            <h3 class="card-title">Parc national des Calanques</h3>
                        </div>
                    </div>
                </a>
                </article>
                <article class="card activite-card">
                    <a href="#">
                    <img class="activite-image" src="./images/activites/florian-wehde.jpg" alt="Image du Vieux-Port">
                    <div class="card-content">
                        <div class="card-txt">
                            <h3 class="card-title">Notre-Dame-de-la-Garde</h3>
                        </div>
                    </div>
                </a>
                </article>
            </div>
        </section>
        
        <p></p>
        <footer>
            <section class="card-service">
                <a href="#">
                    <div class="card-txt">

                        <h3 class="card-title">A propos</h3>
                        <p class="card-subtitle">Fonctionnement</p>
                        <p class="card-subtitle">Conditions générales</p>
                        <p class="card-subtitle">Données et confidentialité</p>
                    </div>
                </a>

                <a href="#">
                    <div class="card-txt">

                        <h3 class="card-title">Nos hébergements</h3>
                        <p class="card-subtitle">Charte qualité</p>
                        <p class="card-subtitle">Proposer votre hôtel</p>
                    </div>
                </a>

                <a href="#">
                    <div class="card-txt">

                        <h3 class="card-title">Assistance</h3>
                        <p class="card-subtitle">Centre d'aide</p>
                        <p class="card-subtitle">Nous contacter</p>
                    </div>
                
                </a>

                </section>

        </footer>
    </div>

<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>


<script id="define-custom-element-wtd-root">
      (() => {
        window.customElements.whenDefined('wtd-root').then(() => {
          window.dispatchEvent(
            new CustomEvent('customElements.defined', {
                detail: {
                  name: 'wtd-root',
                },
            }),
          );
        });

        if (window.customElements.get('wtd-root')) return;

        window.customElements.define('wtd-root', class extends HTMLElement {
          constructor() {
            super();
            this.attachShadow({ mode: 'open' });
          }
        });
      })();
    </script><wtd-root id="cashback"></wtd-root><script id="define-custom-element-wtd-div">
      (() => {
        window.customElements.whenDefined('wtd-div').then(() => {
          window.dispatchEvent(
            new CustomEvent('customElements.defined', {
                detail: {
                  name: 'wtd-div',
                },
            }),
          );
        });

        if (window.customElements.get('wtd-div')) return;

        window.customElements.define('wtd-div', class extends HTMLElement {
          constructor() {
            super();
            
          }
        });
      })();
    </script><script>window.wtdExtensionInjected = true</script><wtd-div id="wanteeedContainer" style="position: fixed; display: block; top: 0px; right: 0px; z-index: 2147483647;"><wtd-root id="comparator"></wtd-root><iframe id="wanteeedPanel" data-version="1.90.0" allowtransparency="true" style="background-color: rgb(255, 255, 255); border: none; border-radius: 3px; box-shadow: rgb(181, 181, 181) 1px 1px 3px 2px; clip: auto; display: none; margin-left: auto; margin-right: 12px; margin-top: 12px; position: relative; z-index: 2147483647; height: 1px; width: 1px;"></iframe></wtd-div><iframe id="wanteeedTestMaker" data-version="1.90.0" allowtransparency="true" style="border: none; clip: auto; display: none; left: 0px; overflow: hidden; position: fixed; top: 10px; transition: all 0.2s ease-out 0s; z-index: 45739864; height: 1px; width: 1px;"></iframe></body></html>
