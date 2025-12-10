---
title: Contexte
description: Contexte du guide éditorial
---

<div class="o-tabs js-tabs">
    <ul class="js-tablist" data-hx="h2">
        <li class="js-tablist__item">
            <a href="#tabs-01" class="js-tablist__link">Documents de référence</a>
        </li>
        <li class="js-tablist__item">
            <a href="#tabs-02" class="js-tablist__link">Composants de la SNOMED CT</a>
        </li>
        <li class="js-tablist__item">
            <a href="#tabs-03" class="js-tablist__link">Principes hérités du <i>French Translation Collaboration Group</i></a>
        </li>
        <li class="js-tablist__item">
            <a href="#tabs-04" class="js-tablist__link">Édition nationale française</a>
        </li>
    </ul>
    <div class="js-tabcontent--container">
        <div id="tabs-01" class="js-tabcontent">
            <!-- Onglet 1 - Documents de référence -->
            <table>
                <thead>
                    <tr><th>Catégorie</th><th>Documents de référence</th></tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Guides éditoriaux de la SNOMED CT</td>
                        <td><div class="wysiwyg"><ul>
                            <li>Espace de traduction : <a href="https://confluence.ihtsdotools.org/display/tran/translations+home">https://confluence.ihtsdotools.org/display/tran/translations+home</a></li>
                            <li>Guide éditorial international : <a href="http://snomed.org/eg">http://snomed.org/eg</a></li>
                            <li><i>Translation User Group</i> : <a href="https://confluence.ihtsdotools.org/display/TRANSLATIONUSERGROUP">https://confluence.ihtsdotools.org/display/TRANSLATIONUSERGROUP</a> (v 2.28)</li>
                        </ul></div></td>
                    </tr>
                    <tr>
                        <td>Règles grammaticales, orthographiques et syntaxiques de la langue française</td>
                        <td><div class="wysiwyg"><ul>
                            <li>Larousse : <a href="https://www.larousse.fr/dictionnaires/francais-monolingue">https://www.larousse.fr/dictionnaires/francais-monolingue</a></li>
                            <li>Le Robert : <a href="https://dictionnaire.lerobert.com/">https://dictionnaire.lerobert.com/</a></li>
                            <li>Rectifications orthographiques de 1990 : <a href="https://www.dictionnaire-academie.fr/annexes/rectifications-orthographe.html">https://www.dictionnaire-academie.fr/annexes/rectifications-orthographe.html</a></li>
                        </ul></div></td>
                    </tr>
                    <tr>
                        <td>Dictionnaires médicaux et bases de données médicales et pharmacologiques</td>
                        <td><div class="wysiwyg"><ul>
                            <li>Agence européenne des médicaments (EMA) : <a href="https://www.ema.europa.eu">https://www.ema.europa.eu</a></li>
                            <li>Agence nationale de sécurité du médicament et des produits de santé (ANSM) :<a href="https://ansm.sante.fr/">https://ansm.sante.fr/</a></li>
                            <li>Dictionnaire de l'Académie nationale de Pharmacie : <a href="https://dictionnaire.acadpharm.org/w/Acadpharm:Accueil">https://dictionnaire.acadpharm.org/w/Acadpharm:Accueil</a></li>
                            <li>Dictionnaire médical de l'Académie de médecine : <a href="https://www.academie-medecine.fr/le-dictionnaire/index.php">https://www.academie-medecine.fr/le-dictionnaire/index.php</a></li>
                            <li>Directives générales pour la formation de dénominations communes internationales applicables aux substances pharmaceutiques : <a href="https://cdn.who.int/media/docs/default-source/international-nonproprietary-names-(inn)/generalprinciplesfr.pdf?sfvrsn=cf4e7818_8">https://cdn.who.int/media/docs/default-source/international-nonproprietary-names-(inn)/generalprinciplesfr.pdf?sfvrsn=cf4e7818_8</a></li>
                            <li>Manuel Merck : <a href="https://www.msdmanuals.com/fr/professional">https://www.msdmanuals.com/fr/professional</a></li>
                            <li>MedNet INN services : <a href="https://extranet.who.int/soinn/">https://extranet.who.int/soinn/</a></li>
                            <li>MeSH bilingue : <a href="http://mesh.inserm.fr/FrenchMesh/">http://mesh.inserm.fr/FrenchMesh/</a></li>
                            <li>Orphanet : <a href="https://www.orpha.net/en/disease">https://www.orpha.net/en/disease</a></li>
                            <li><i>Standard Terms</i> de l'EDQM : <a href="https://smt.esante.gouv.fr/terminologie-standardterms/">https://smt.esante.gouv.fr/terminologie-standardterms/</a></li>
                            <li><i>Terminologia Anatomica</i> : <a href="https://www.cours-medecine.info/guides-pratiques/bibliotheque/nomenclature-anatomique.html">https://www.cours-medecine.info/guides-pratiques/bibliotheque/nomenclature-anatomique.html</a></li>
                        </ul></div></td>
                    </tr>
                    <tr>
                        <td>Autres Terminologies</td>
                        <td><div class="wysiwyg"><ul>
                            <li>Serveur Multi Terminologies (SMT) de l'ANS : <a href="https://smt.esante.gouv.fr">https://smt.esante.gouv.fr</a></li>
                        </ul></div></td>
                    </tr>
                </tbody>
            </table>
        </div>
        <div id="tabs-02" class="js-tabcontent">
            <!-- Onglet 2 - Composants de la SNOMED CT -->
            <h2>Concepts</h2>
            <p>Les concepts représentent le sens d’une idée clinique unique à laquelle a été associée un identifiant unique. Cet identifiant ne contient aucune information sur le sens du concept.</p>
            <h2>Descriptions</h2>
            <p>Les descriptions sont des termes en langage naturel, lisibles et compréhensibles, associés à un concept. Plusieurs types de descriptions peuvent être associés à un concept :</p>
            <div class="wysiwyg"><ul>
                <li>Le <b>FSN (Fully Specified Name)</b>, qui permet de décrire de manière unique et non ambigüe le sens du concept. Du fait de son rôle, il peut être très éloigné du langage médical, ainsi il n’est pas utilisé lors des échanges de données ;</li>
                <li>Les <b>synonymes</b>, qui permettent de décrire d’une autre manière un même concept.</li>
            </ul></div>
            <br/>
            <p>Chaque concept possède un seul FSN actif. La SNOMED CT permet de spécifier parmi les synonymes lequel est le synonyme « préféré » dans une langue donnée. C’est ce qu’on appelle l’<b>acceptabilité</b> d’une description.</p>
            <div class="wysiwyg"><ul>
                <li>Le <b>FSN</b> est toujours considéré comme « préféré ».</li>
                <li>Il existe toujours un synonyme considéré comme « préféré » dans chaque langue : le <b>terme préféré (PT)</b>. C’est ce terme qui est par défaut utilisé dans les jeux de valeurs ou les échanges de données, en plus de l’identifiant SNOMED CT.</li>
                <li>D’autres synonymes considérés comme « acceptables » peuvent être utilisés comme terme alternatif dans une interface (IHM) par exemple.</li>
            </ul></div>
            <br/>
            <p>La SNOMED CT définit trois valeurs de sensibilité à la casse pour ses descriptions :</p>
            <table>
                <thead>
                    <tr><th>Indicateur</th><th >Abréviation</th><th>Explication</th><th>Utilisation en France</th></tr>
                </thead>
                <tbody>
                    <tr>
                        <td><i>Entire term case insensitive</i></td>
                        <td align="center">ci</td>
                        <td>La casse peut être modifiée (e.g. « rhume »)</td>
                        <td align="center">Oui</td>
                    </tr>
                    <tr>
                        <td><i>Entire term case sensitive</i></td>
                        <td align="center">CS</td>
                        <td>La casse ne peut pas être modifiée (e.g. « Escherichia coli », « pH »)</td>
                        <td align="center">Oui</td>
                    </tr>
                    <tr>
                        <td><i>Only initial character case insensitive</i></td>
                        <td align="center">cI</td>
                        <td>Seule la casse de la première lettre peut être modifiée (e.g. « exérèse avec guidage par IRM »)</td>
                        <td align="center">Oui</td>
                    </tr>
                </tbody>
            </table>
            <h2>Relations</h2>
            <p>Les relations permettent de relier les concepts entre eux. La SNOMED CT contient :</p>
            <div class="wysiwyg"><ul>
                <li>Une relation hiérarchique |est un(e)| (ou |<i>is a</i>| en anglais), elle relie un concept à un autre concept plus générique formant ainsi les hiérarchies au sein de la SNOMED CT</li>
                <li>Des relations non hiérarchiques qui permettent de définir des caractéristiques d’un concept (agent pathogène, localisation, méthode utilisée, …). Elles peuvent lier un concept à un autre concept ou à une valeur numérique.</li>
            </ul></div>
        </div>
        <div id="tabs-03" class="js-tabcontent">
            <!-- Onglet 3 - Principes hérités du French Translation Collaboration Group -->
            <p>Ce groupe de travail de la SNOMED International a pour objectif de produire un ensemble de règles et une traduction de l’édition internationale de la SNOMED CT commune à l’ensemble des pays francophones membres du groupe, la Common French. Il regroupe les NRC de Belgique, du Canada, de France, du Luxembourg et de Suisse ainsi que des industriels et des établissements publics originaires des pays précédemment cités.</p>
            <p>Chaque NRC est responsable de la traduction des concepts publiés dans son édition nationale. Il peut utiliser la Common French et changer, si nécessaire, l’acceptabilité des descriptions en fonction de ses besoins nationaux. Par ailleurs, un pays membre peut considérer une traduction de la Common French comme non acceptable, celle-ci ne sera alors pas utilisée dans sa traduction nationale.</p>
            <p>Enfin, en fonction des spécificités nationales qui lui sont propres, un NRC peut décider de ne pas utiliser certaines règles ou d’en créer de nouvelles pour répondre à ces spécificités. Néanmoins l’objectif est de garder une homogénéité dans les règles entre les pays du groupe.</p>
            <p>Le groupe est ouvert à toute personne souhaitant contribuer. Pour plus d’informations vous pouvez vous reporter à la page Confluence du groupe : <a href="https://confluence.ihtsdotools.org/display/FTCG/French+Translation+Collaboration+Group">https://confluence.ihtsdotools.org/display/FTCG/French+Translation+Collaboration+Group</a>.</p>
            <p>Les sections suivantes présentent les principes de traduction suivis par le groupe et répercutés de facto sur les traductions françaises.</p>
            <h2>Traduction onomasiologique</h2>
            <p>La traduction se fait à l’échelle du concept et non à celle des descriptions. La traduction débute donc par la compréhension du sens du concept (via son FSN, sa définition logique et sa position dans la SNOMED CT) puis un ensemble de synonymes est choisi pour représenter ce sens en français. Par exemple, la notion « <i>inpatient environment</i> » ne contient pas explicitement la notion de soin mais afin de clarifier le sens du concept la traduction est « environnement de soins pour patient(e)s hospitalisé(e)s ».</p>
            <p>Ces synonymes doivent :</p>
            <div class="wysiwyg"><ul>
                <li>Respecter les règles éditoriales de la SNOMED Int. ;</li>
                <li>Ne pas avoir de signification plus précise ou plus générique que celle du FSN anglais du concept.</li>
            </ul></div>
            <br/>
            <p>La présence de doublons entre plusieurs concepts est proscrite.</p>
            <h2>Absence de traduction des FSN</h2>
            <p>Comme la majorité des pays membres du groupe, la France a décidé de ne pas traduire les FSN des concepts de l’édition internationale. En effet :</p>
            <div class="wysiwyg"><ul>
                <li>Dans le cadre de l’échange de données, ce sont les synonymes et non le FSN qui doivent accompagner l’identifiant SNOMED CT. Le FSN ne doit également pas être utilisé dans les applications de santé. Il n’y a donc pas de réel besoin de traduction des FSN.</li>
                <li>La traduction peut amener des variations dans les subtilités d’une langue à une autre. Le FSN étant le garant du sens du concept, il nous paraît essentiel d’éviter toute interprétation et modification de ce sens par la traduction.</li>
            </ul></div>
            <br/>
            <p>Ainsi seuls les termes préférés et les synonymes acceptables sont traduits.</p>
            <h2>Prise en compte des rectifications orthographiques de 1990</h2>
            <p>Les rectifications orthographiques publiées en 1990 visent à simplifier et corriger certaines incohérences de la langue française. Ces rectifications sont des recommandations mais sont, cependant, enseignées dans de nombreux territoires francophones. Le <i>French Translation Collaboration Group</i> a donc décidé d’en tenir compte dans ses travaux de traductions tout en acceptant la présence de synonymes utilisant l’ancienne orthographe.</p>
        </div>
        <div id="tabs-04" class="js-tabcontent">
            <!-- Onglet 4 - Édition nationale française -->
            <p>L’édition française de la SNOMED CT intègre directement la version de l’édition internationale de laquelle elle dépend (celle du mois de mai précédent) ainsi que l’extension française de SNOMED CT.</p>
            <p>L’édition française est publiée annuellement au mois de juin depuis 2024. Elle contient des traductions provenant en majorité de la <i>Common French</i> de la SNOMED CT créé en collaboration au sein du <i>French Translation Collaboration Group</i>. L’ANS ajuste ensuite l’acceptabilité des descriptions de la <i>Common French</i> en fonction des usages français. Elle peut aussi ajouter, corriger ou inactiver des descriptions. Des travaux de contrôle qualité sont en cours afin d’homogénéiser les traductions faites avant l’arrivée de l’ANS dans le <i>French Translation Collaboration Group</i>.</p>
            <p>Pour les demandes d’évolution (création, inactivation ou modification) vous pouvez vous référer à la documentation du SMT : <a href="https://smt.esante.gouv.fr/assistance/documentation-snomed-ct/demande-devolution-et-contribution/">https://smt.esante.gouv.fr/assistance/documentation-snomed-ct/demande-devolution-et-contribution/</a>.</p>
        </div>
    </div>
</div>