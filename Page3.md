---
layout: page
title: Interests and Publications
image: assets/images/pic03.jpg
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">
    <!-- Publications Section -->
    <section id="one">
        <div class="inner">
            <header class="major" style="text-align: center;">
                <h2 style="color: rgb(21, 92, 207);">PUBLICATIONS</h2>
            </header>
            <div class="row">
                <h3 style="text-align: center;">Check out my research profiles:</h3>
                <p style="text-align: center;">
                    <a href="https://scholar.google.com/citations?user=Y2xrl_8AAAAJ&hl=en" target="_blank">
                        <img src="{% link assets/images/google.png %}" alt="Google Scholar" 
                             style="width: 45px; height: 45px; margin: 10px;">
                    </a>
                    <a href="https://orcid.org/0009-0009-7069-5729" target="_blank">
                        <img src="{% link assets/images/orcid.png %}" alt="ORCID" 
                             style="width: 45px; height: 45px; margin: 10px;">
                    </a>
                    <a href="https://www.researchgate.net/profile/Kartav-Kesri?ev=hdr_xprf" target="_blank">
                        <img src="{% link assets/images/research.png %}" alt="ResearchGate" 
                             style="width: 45px; height: 45px; margin: 10px;">
                    </a>
                </p>
                <div class="12u 12u$(small)">
                    <ol>
                        <li>
                            <b style="color: #F4D03F;">Dependence of spicule properties on magnetic field — results from Magnetohydrodynamics simulations</b><br>
                            <b>Kartav Kesri</b>, S. Dey, P. Chatterjee, R. Erdelyi<br>
                            <a href="https://iopscience.iop.org/article/10.3847/1538-4357/ad67d8" style="color: #5DADE2;" target="_blank">
                                DOI: 10.3847/1538-4357/ad67d8
                            </a><br>
                            <i>The Astrophysical Journal</i>
                        </li>
                        <li>
                            <b style="color: #F4D03F;">MC Escher's Print Gallery</b><br>
                            M. Choudhary, <b>Kartav Kesri</b><br>
                            <a href="https://www.mtai.org.in/wp-content/uploads/2022/12/blackboard-issue-5.pdf" style="color: #5DADE2;" target="_blank">
                                <i>Blackboard Journal, Issue 5, Editorial 3</i>
                            </a><br>
                            <i>Mathematics Teachers Association, India</i>
                        </li>
                    </ol>
                </div>
            </div>
        </div>
    </section>
</div>

<!-- Research Interests -->
<section id="one">
    <div class="inner">
        <header class="major" style="text-align: center;">
            <h2 style="color: rgb(21, 92, 207);">RESEARCH INTERESTS</h2>
        </header>
        <p style="text-align: justify;">
            As an early Master's student, my research interests are broad, but I am particularly drawn to <b>Astronomy and Astrophysics</b>. Below is a brief overview of my current interests, though I am eager to expand my understanding into <b>interdisciplinary topics</b> as well.
        </p>
    </div>
</section>

<!-- Research Topics -->
<style>
    .spotlights {
        display: flex;
        flex-direction: column;
        gap: 30px;
    }

    .spotlights section {
        display: flex;
        align-items: center;
        justify-content: space-between;
        flex-wrap: wrap;
        width: 100%;
        max-width: 1350px;
        margin: auto;
        padding: 20px;	
        border-radius: 10px;
        box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
    }

    .spotlights img {
        width: 40%;
        height: 325px;
        object-fit: cover;
        border-radius: 10px;
    }

    .spotlights .content {
        width: 55%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        text-align: justify;
    }

    @media (max-width: 900px) {
        .spotlights section {
            flex-direction: column;
            text-align: center;
        }

        .spotlights img {
            width: 100%;
            height: auto;
        }

        .spotlights .content {
            width: 100%;
        }
    }
</style>

<section id="two" class="spotlights">
    <section>
        <img src="{% link assets/images/RT.png %}" alt="MHD Simulations" />
        <div class="content">
            <header class="major">
                <h3>Astrophysical Fluid Dynamics (MHD, rMHD, GRMHD)</h3>
            </header>
            <p>
                Fluid dynamics plays a crucial role in various astrophysical environments, from <b>solar plasma</b> to <b>accretion disks around black holes and neutron stars</b>. Beyond astrophysics, numerical fluid dynamics also has applications in climate studies and industrial processes.
                <br /><br />
                My primary exposure has been through <b>MHD simulations</b> while studying Solar Spicules, using the well-known <b>PLUTO CODE</b>. This research also led me to explore solar flares, coronal mass ejections (CMEs), and varous other properties that can led to the formation of these ubiquitous structures.
                <br /><br />
                I am actively expanding my knowledge in Computational Fluid Dynamics (CFD) through different pipelines, besides Python-based approaches.
            </p>
        </div>
    </section>   
    <section>
        <img src="{% link assets/images/PIC.png %}" alt="General Relativity" />
        <div class="content">
            <header class="major">
                <h3>General Relativity, Binary Mergers, Shocks and PIC Simulations</h3>
            </header>
            <p>
                General Relativity (GR) is one of the most fascinating subjects in physics, filled with open questions awaiting exploration. My interest lies at the intersection of GR and MHD simulations, particularly in the context of Binary Black Hole (BBH) and Binary Neutron Star (BNS) mergers.
                <br /><br />
				Currently, I am exploring the Particle in Cell Simulations to analyse the Relativistic Collisonless Shcoks that can eventually lead to the formation of GRBs originating from such mergers.
            </p>
        </div>
    </section>   
    <section>
        <img src="{% link assets/images/BS.png %}" alt="Buchdahl Stars" />
        <div class="content">
            <header class="major">
                <h3>Buchdahl Stars</h3>
            </header>
            <p>
                Not much has been researched when it comes to Buchdahl Stars, but for some reason this has always peeked my interest.It is belived to be the newest addition in the category of compact objects after WDs, NSs and BHs, if they are ever observed succesfully. 
                <br /><br />
            	BSs are believed to be that dead stars which has the maximum compactness while still pertaining a timelike boundary, i.e., star at the Buchdahl limit of M/R=4/9. It has the compactness greater than that of Neutron Stars but slighlty smaller than the Black holes. A static BS can be defined using the Schwarszchild metric even though it doesn't has any Event Horizon. 
				<br/><br/>
				It is indeed one of the most interesting topics to be explored upon and in the future, I would like to delve deeper into the integrity of its internal structure.
            </p>
        </div>
    </section>
</section>



<p><em>Last Updated: April 3rd, 2025</em></p>
