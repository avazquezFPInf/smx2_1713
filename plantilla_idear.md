# Dossier de l’equip · Bloc 1: Idear

Projecte: [Escriviu el nom]
Equip i membres: [Noms]
Enllaç al Trello: [Enllaç]
Enllaç a la carpeta d’evidències: [Enllaç]
Darrera actualització: [Data]

## Com utilitzar aquesta plantilla

Copieu-la en un únic document compartit de l’equip. Substituïu els camps entre claudàtors. Manteniu el mateix document durant tot el bloc: reviseu-lo i afegiu-hi les evidències cada dia. No cal saber programar per completar-lo. Si encara no sabeu una resposta, escriviu «Pendent de consultar» i anoteu el dubte a l’apartat 8. Al final de cada sessió, reserveu cinc minuts per actualitzar el diari i el Trello.

## Què hem d’omplir cada dia?

| Sessió | Apartats que cal treballar | Evidència mínima |
| --- | --- | --- |
| 19/10 | 1 i 2: necessitat, destinataris i idea | Primera proposta contrastada |
| 20/10 | 2: benefici i participació; 9: diari | Acords i enllaç al Trello |
| 22/10 | 1–3: proposta i exemple d’ús; 6–7: primers dibuixos | Document inicial i fotos dels esbossos |
| 26/10 | 8: retorn; 4: primeres fitxes | Canvis acordats i funcionalitats inicials |
| 27/10 | 4, 6 i 7: actualitzar funcionalitats i dibuixos | Mateixos codis F01, F02… al document i al dibuix |
| 29/10 | 4–7: prioritats, recorregut, arquitectura i wireframes | Llista d’imprescindibles i opcionals |
| 2/11 | Sense sessió prevista al calendari del projecte | No cal cap actualització |
| 3/11 | 4 i 8: revisió amb el professorat | Dubtes, recursos i decisions registrats |
| 5/11 | 4 i 6: completar fitxes, proves i recursos | Una prova verificable per funcionalitat imprescindible |
| 9/11 | Revisió de tots els apartats i checklist final | Dossier validat i enllaçat al Trello |

## 1. Quina necessitat volem resoldre?

- Quin problema concret heu observat? [Expliqueu-lo en 2–3 frases.]
- A qui li passa? [Identifiqueu les persones destinatàries.]
- Com sabeu que existeix? [Observació, conversa o font consultada; afegiu-ne l’enllaç si escau.]
- Què passa ara quan aquesta persona necessita ajuda? [Situació actual.]

## 2. Quina solució proposem?

- La nostra proposta consisteix a… [Expliqueu què fareu amb paraules senzilles.]
- Ajudarà perquè… [Benefici solidari concret.]
- A la Jornada, els companys podran… [Acció que podran fer o provar.]
- Sabrem que ha estat útil si… [Un indicador senzill: per exemple, poden trobar la informació sense ajuda.]
- Qui farà servir el producte? [Participant, voluntari, organització… Només els rols necessaris.]
- Què quedarà fora del projecte? [Idees que no fareu en aquesta primera versió.]

## 3. Exemple d’ús complet

Descriviu una situació realista abans de fer la llista de funcionalitats.

- Persona i necessitat: [Qui és i què vol aconseguir?]
- Punt de partida: [Què té davant?]
- Pas 1: [Què fa?]
- Pas 2: [Què fa?]
- Pas 3: [Què rep o veu?]
- Resultat final: [Com queda resolta la necessitat?]
- Si alguna cosa falla: [Quin missatge o alternativa trobarà?]

## 4. Funcionalitats: què podrà fer el producte?

Una funcionalitat és una acció útil per a una persona. «Consultar els punts de recollida» és una funcionalitat. «Fer el menú» és una tasca de construcció. «Que sigui bonic» no explica cap acció comprovable.

Comenceu amb poques funcionalitats: com a orientació, 3–5 imprescindibles. Si en necessiteu més o menys, acordeu-ho amb el professorat. El conjunt d’imprescindibles és el producte mínim viable (MVP): la versió més petita que ja és útil.

### Llista resum

| Codi | Nom amb un verb | Qui l’utilitza? | Imprescindible / opcional | Pantalla o component |
| --- | --- | --- | --- | --- |
| F01 | [Consultar…] | [Persona] | [Prioritat] | [P01 / C01] |
| F02 | [Acció] | [Persona] | [Prioritat] | [Referència] |
| F03 | [Acció] | [Persona] | [Prioritat] | [Referència] |

### Fitxa per repetir per a cada funcionalitat

- Codi i nom: [F01 · Verb + objecte.]
- Qui la necessita i per què? [Persona i benefici.]
- Què ha de passar abans? [Condició inicial; si no n’hi ha, indiqueu-ho.]
- Què introdueix o selecciona la persona? [Dades, opció o botó; pot ser «Res».]
- Passos: [1. Acció de la persona. 2. Resposta del producte. 3. Resultat.]
- Què ha de veure o obtenir al final? [Resultat concret.]
- Què passarà si falta informació o hi ha un error? [Resposta entenedora o alternativa.]
- Prioritat i motiu: [Imprescindible / opcional, perquè…]
- On es veu? [P01 al wireframe o C01 a l’arquitectura.]
- Com comprovarem que funciona? [Situació inicial + acció + resultat esperat.]
- Tasques relacionades al Trello: [Enllaços; es detallaran al bloc 2.]

### Exemple resolt · No el copieu com si fos el vostre projecte

- Codi i nom: F01 · Consultar els punts de recollida d’aliments.
- Persona i benefici: una participant vol saber on pot portar aliments.
- Condició inicial: hi ha una llista de punts amb nom, adreça i horari.
- Entrada: prem «On puc portar aliments?».
- Passos: obre la portada, prem el botó i consulta la llista.
- Resultat: veu el nom, l’adreça i l’horari dels punts disponibles.
- Cas alternatiu: si no hi ha punts, veu «Encara no hi ha punts disponibles. Consulta l’organització».
- Prioritat: imprescindible, perquè sense aquesta informació no sabrà on anar.
- Dibuix: P01 (portada) → P02 (llista de punts).
- Prova: amb dos punts preparats, prem el botó; han d’aparèixer tots dos amb adreça i horari. Repetiu la prova amb una llista buida per comprovar el missatge.
- Possible tasca de Trello: preparar la llista de punts. La funcionalitat descriu el resultat; aquesta tasca és una part de la feina per construir-lo.

## 5. Recorregut principal

Escriviu i dibuixeu el camí més important, amb els codis de les funcionalitats.

[Inici / P01] → [Acció F01 / P02] → [Resultat]

- Com torna enrere la persona? [Resposta.]
- Què passa si no pot acabar? [Alternativa.]
- Si no és una aplicació: [Dibuixeu els passos de l’activitat o del servei.]

## 6. Arquitectura senzilla: quines peces necessitem?

L’arquitectura explica les peces de la solució, què fa cadascuna i com es connecten. No cal fer servir totes les peces d’un sistema professional ni decidir tecnologies que encara no coneixeu.

Dibuixeu caixes i fletxes, a mà si voleu. Poseu un nom i un codi a cada peça. Escriviu sobre les fletxes què circula: informació, una petició o una connexió.

Exemple de web informativa: [Participant amb navegador] → [Web amb la llista de punts]. La informació pot estar escrita a la mateixa web; no cal una base de dades per defecte.

Exemple amb equips: [Participant] → [Ordinador de consulta] → [Informació del servei]. Afegiu la xarxa, el servidor o altres dispositius només si els necessiteu.

- Dibuix o fotografia: [Enganxeu-lo aquí.]

| Codi i peça | Què fa? | Amb què es connecta? | Què necessitem per tenir-la? |
| --- | --- | --- | --- |
| C01 · [Peça] | [Funció] | [Altra peça i informació que intercanvien] | [Equip, programa, accés…] |

- On és la informació i qui l’actualitza? [Resposta.]
- Cal guardar dades? Quines i per què? [Si no cal, escriviu «No cal guardar dades».]
- Recursos que ja tenim: [Llista.]
- Recursos o permisos pendents: [Llista i qui ho consultarà.]
- Si falla Internet o un dispositiu: [Alternativa senzilla per a la Jornada.]
- Dades de prova: [Utilitzeu dades inventades. No poseu contrasenyes ni dades personals reals al dossier o als dibuixos.]

## 7. Wireframes: com seran les pantalles?

Un wireframe és un esbós de pantalla: mostra on van el títol, la informació, els botons i els camps. Pot ser en paper, amb rectangles i text. No calen colors, logotips ni programació.

1. Trieu el recorregut principal de l’apartat 5.
2. Dibuixeu una pantalla per cada pas necessari i numereu-les P01, P02…
3. Poseu textos i noms de botó concrets: «Veure punts», en lloc de «Botó».
4. Connecteu els botons amb fletxes a la pantalla de destinació.
5. Escriviu al costat les funcionalitats F01, F02… que cobreix cada pantalla.
6. Dibuixeu un estat alternatiu important, com una llista buida o un camp sense omplir.
7. Demaneu a un altre equip que segueixi el recorregut sense explicar-l’hi. Anoteu què no entén.
8. Feu una foto llegible dels dibuixos i afegiu-la al document.

Exemple: P01 «Campanya solidària», amb el botó «On puc portar aliments?» → P02 «Punts de recollida», amb la llista d’adreces i el botó «Tornar» → P01.

- Fotografies o enllaços: [Afegiu-los aquí.]
- Relació pantalla–funcionalitat: [P01 → F01; P02 → F01…]
- Què no ha entès l’altre equip? [Observació.]
- Què hem canviat després de la prova? [Canvi.]
- Si no hi ha pantalles: [Indiqueu «No aplica» i afegiu un esquema de l’activitat, amb passos, materials i decisions.]

Aquests són esbossos inicials per definir la idea. Al bloc 3 els revisareu i els convertireu en un prototip més complet.

## 8. Retorn, dubtes i decisions

| Data | Comentari o dubte | Decisió / canvi | Qui el resol? | Estat |
| --- | --- | --- | --- | --- |
| [Data] | [Què ens han dit o què no sabem?] | [Què farem?] | [Nom] | [Pendent / resolt] |

## 9. Diari de treball · Afegiu una fila cada sessió

| Data | Qui ha participat? | Què hem fet i en quin apartat? | Evidència / Trello | Següent pas |
| --- | --- | --- | --- | --- |
| [Data] | [Noms] | [Canvi concret] | [Enllaç o foto] | [Acció i responsable] |

## Checklist per a la validació del 9/11

- [ ] Tothom de l’equip pot explicar la necessitat i el benefici solidari.
- [ ] La proposta incorpora el retorn del professorat.
- [ ] Hem separat les funcionalitats imprescindibles de les opcionals.
- [ ] Cada funcionalitat imprescindible té una fitxa amb resultat, cas alternatiu i prova.
- [ ] El recorregut principal, l’arquitectura i els wireframes són coherents amb les fitxes.
- [ ] Els dibuixos són llegibles i tenen codis; si no hi ha pantalles, hem justificat l’alternativa.
- [ ] Sabem quins recursos falten i hem registrat els dubtes pendents.
- [ ] El diari està actualitzat i el document està enllaçat al Trello.
- [ ] Hem comprovat que el professorat pot obrir els enllaços i les fotografies.

Per validar: obriu el dossier, expliqueu el recorregut amb els dibuixos i mostreu una fitxa de funcionalitat amb la seva prova. Encara no cal que el producte estigui construït.
