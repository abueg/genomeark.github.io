---
assembly_status: <em style="color:maroon">No assembly</em>
common_name: Savannah sparrow
data_arima-1_bases: '147818247451'
data_arima-1_scale: '1.9160'
data_arima-2_bases: 147.82 Gbp
data_arima-2_bytes: 71.9 GiB
data_arima-2_coverage: 125.48x
data_arima-2_links: s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/arima/<br>
data_arima-2_s3gui: https://42basepairs.com/browse/s3/genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/arima/
data_arima-2_s3url: https://genomeark.s3.amazonaws.com/index.html?prefix=species/Passerculus_sandwichensis/bPasSan2/genomic_data/arima/
data_arima-2_scale: 1.9160
data_arima_bases: 147.82 Gbp
data_arima_bytes: 71.9 GiB
data_arima_coverage: 125.48x
data_bionano-1_bases: '447082834941'
data_bionano-1_scale: '588.5017'
data_bionano-2_bases: N/A
data_bionano-2_bytes: 724.5 MiB
data_bionano-2_coverage: 379.53x
data_bionano-2_links: s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/bionano/<br>
data_bionano-2_s3gui: https://42basepairs.com/browse/s3/genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/bionano/
data_bionano-2_s3url: https://genomeark.s3.amazonaws.com/index.html?prefix=species/Passerculus_sandwichensis/bPasSan2/genomic_data/bionano/
data_bionano-2_scale: 588.5017
data_bionano_bases: N/A
data_bionano_bytes: 724.5 MiB
data_bionano_coverage: 379.53x
data_pacbiohifi_fqgz-1_bases: '54579979164'
data_pacbiohifi_fqgz-1_scale: '1.2210'
data_pacbiohifi_fqgz-2_bases: 54.58 Gbp
data_pacbiohifi_fqgz-2_bytes: 41.6 GiB
data_pacbiohifi_fqgz-2_coverage: 46.33x
data_pacbiohifi_fqgz-2_links: s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/pacbio_hifi/<br>
data_pacbiohifi_fqgz-2_s3gui: https://42basepairs.com/browse/s3/genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/pacbio_hifi/
data_pacbiohifi_fqgz-2_s3url: https://genomeark.s3.amazonaws.com/index.html?prefix=species/Passerculus_sandwichensis/bPasSan2/genomic_data/pacbio_hifi/
data_pacbiohifi_fqgz-2_scale: 1.2210
data_pacbiohifi_fqgz_bases: 54.58 Gbp
data_pacbiohifi_fqgz_bytes: 41.6 GiB
data_pacbiohifi_fqgz_coverage: 46.33x
data_status: '''<em style="color:forestgreen">PacBio HiFi</em> ::: <em style="color:forestgreen">Arima</em>'''
data_use_source: from-default
data_use_text: Samples and data come from a variety of sources. To support fair and
  productive use of this data, please abide by the <a href="https://genome10k.soe.ucsc.edu/data-use-policies/">Data
  Use Policy</a> and contact Erich D. Jarvis, ejarvis@rockefeller.edu, with any questions.
genbank_alt: bPasSan1:GCA_022578375.1
genbank_pri: bPasSan1:GCA_022577445.1
genome_size: 1178000000
genome_size_display: 1.18 Gbp
genome_size_method: GoAT
last_raw_data: 1678303917
last_updated: 1678314151
mds:
- data: "species: Passerculus sandwichensis\nspecimen: bPasSan2\nprojects: \n  - vgp\ndata_location:
    S3\nrelease_to: S3\nprimary: s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/assembly_vgp_standard_2.0/bPasSan2.standard.pri.20230308.fasta.gz\nhaplotigs:
    s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/assembly_vgp_standard_2.0/bPasSan2.standard.alt.20230308.fasta.gz\npretext:
    s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/assembly_vgp_standard_2.0/evaluation/pri/pretext/bPasSan2_pri__s2.heatmap.pretext\nkmer_spectra_img:
    s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/assembly_vgp_standard_2.0/evaluation/merqury/bPasSan2_png/\nmito:
    s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/assembly_MT_rockefeller/bPasSan2.MT.20230307.fasta.gz\npacbio_read_dir:
    s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/pacbio_hifi/\npacbio_read_type:
    hifi\nhic_read_dir: s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/arima/\nbionano_cmap_dir:
    s3://genomeark/species/Passerculus_sandwichensis/bPasSan2/genomic_data/bionano/\npipeline:\n
    \ - hifiasm (0.18.8+galaxy1)\n  - solve (3.7)\n  - yahs (1.2a.2+galaxy0)\nassembled_by_group:
    Rockefeller\nnotes: This was a primary/alternate assembly of bPasSan2 (VGL-bPasSan1).
    This individual had bionano data. HiC scaffolding was performed with yahs. The
    HiC prep was Arima kit 2. This sample arrived with metadata indicating it is a
    female. "
  ident: md4
  title: assembly_vgp_standard_2.0/bPasSan2.yml
metadata: |
  species:
    name: Passerculus sandwichensis
    individuals:
    - short_name: bPasSan1
    short_name: bPasSan
    taxon_id: '161624'
    common_name: Savannah sparrow
    genome_size: 1178000000
    genome_size_method: GoAT
    order:
      name: Passeriformes
    family:
      name: Passerellidae
    project: [ vgp ]
mito2date: 2023-03-07
mito2filesize: 5.4 KiB
mito2length: '16778'
mito2n50ctg: 0
mito2n50scf: 0
mito2seq: https://s3.amazonaws.com/genomeark/species/Passerculus_sandwichensis/bPasSan2/assembly_MT_rockefeller/bPasSan2.MT.20230307.fasta.gz
mito2sizes: |
  <table class="sequence-sizes-table">
  <thead>
  <tr>
  <th></th>
  <th colspan=2 align=center>Contigs</th>
  <th colspan=2 align=center>Scaffolds</th>
  </tr>
  <tr>
  <th>NG</th>
  <th>LG</th>
  <th>Len</th>
  <th>LG</th>
  <th>Len</th>
  </tr>
  </thead>
  <tbody>
  <tr><td> 10 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr><td> 20 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr><td> 30 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr><td> 40 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr style="background-color:#cccccc;"><td> 50 </td><td> 0 </td><td style="background-color:#ff8888;">  </td><td> 0 </td><td style="background-color:#ff8888;">  </td></tr><tr><td> 60 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr><td> 70 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr><td> 80 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr><td> 90 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr><tr><td> 100 </td><td> 0 </td><td>  </td><td> 0 </td><td>  </td></tr></tbody>
  <tfoot>
  <tr><th> 0.000x </th><th> 1 </th><th> 16.78 Kbp </th><th> 1 </th><th> 16.78 Kbp </th></tr>
  </tfoot>
  </table>
mito2version: assembly_MT_rockefeller
name: Passerculus sandwichensis
name_: Passerculus_sandwichensis
short_name: bPasSan
taxon_id: '161624'
---
