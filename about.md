---
layout: page
title: ABOUT
order: 20
---

Neuroalgebra is a collaborative project spearheaded by the 
[UCL Laboratory of Synaptic Imaging](https://www.ucl.ac.uk/ion/research/research-departments/department-clinical-and-experimental-epilepsy/experimental-research-4). The dedicated team behind this initiative includes:
- **Leonid P. Savtchenko**
- **Dmitri A. Rusakov**

Our team's scholarly contributions, reflecting our research on [ARACHNE]({% link arachne.md %}) 
and [ASTRO]({% link astro.md %}), include the following publications:

1. [**Disentangling Astroglial Physiology with a Realistic Cell Model in Silico.**](https://www.nature.com/articles/s41467-018-05896-w)  
   Savtchenko LP, Bard L, Jensen TP, Reynolds JP, Kraev I, Medvedev N, Stewart MG, Henneberger C, Rusakov DA.  
   *Nat Commun. 2018 Sep 3;9(1):3554. doi: 10.1038/s41467-018-05896-w.*

2. [**ARACHNE: A Neural-Neuroglial Network Builder with Remotely Controlled Parallel Computing.**](https://pubmed.ncbi.nlm.nih.gov/28362877/)  
   Aleksin SG, Zheng K, Rusakov DA, Savtchenko LP.  
   *PLoS Comput Biol. 2017 Mar 31;13(3):e1005467. doi: 10.1371/journal.pcbi.1005467.*

3. [**Tonic GABAA Conductance Bidirectionally Controls Interneuron Firing Pattern and Synchronization in the CA3 Hippocampal Network.**](https://pubmed.ncbi.nlm.nih.gov/24344272/)  
   Pavlov I, Savtchenko LP, Song I, Koo J, Pimashkin A, Rusakov DA, Semyanov A.  
   *Proc Natl Acad Sci U S A. 2014 Jan 7;111(1):504-9. doi: 10.1073/pnas.1308388110.*

4. [**Volume-Transmitted GABA Waves Pace Epileptiform Rhythms in the Hippocampal Network.**](https://www.cell.com/current-biology/pdf/S0960-9822(23)00191-4.pdf)  
   Magloire V, Savtchenko LP, T Jensen, S Sylantyev, O Kopach, N Cole, O Tyurikova, D M Kullmann, M C Walker, J S Marvin, LL Looger, JP Hasseman, I Kolb, I Pavlov, Rusakov DA.  
   *Current Biology 33 (7), 1249-1264. e7*

If you need support please join Neuroalgebra forum and ask your question. If you have any 
suggestions about our tools or about the Web site, please feel free to share them with us via 
<span class="about-email" onclick="openEmailClient()">Email</span>.

<script>
function openEmailClient() {
  function oES() {
    var empty = '' + ' ' + String.fromCharCode(32); 
    return empty.trim();
  }

  function genEmail() {
    var user = 'sav'+oES()+'tch'+oES()+'enko';
    var s1 = String.fromCharCode(64);
    var s2 = String.fromCharCode(46);
    var domain = 'ya'+oES()+'hoo' + s2 + 'com';
    return user + s1 + oES() + domain;
  }

  window.location.href = 'mailto:' + genEmail();
}
</script>

