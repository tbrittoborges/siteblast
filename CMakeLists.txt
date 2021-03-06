cmake_minimum_required(VERSION 3.12)
project(siteblast_040938_4 C)

set(CMAKE_C_STANDARD 11)

include_directories(.)
include_directories(distribution)

add_executable(siteblast_040938_4
        distribution/args.c
        distribution/args.h
        distribution/astack.c
        distribution/bz_align.c
        distribution/bz_all.h
        distribution/bz_census.c
        distribution/bz_census.h
        distribution/bz_chain.c
        distribution/bz_dna.c
        distribution/bz_dna.h
        distribution/bz_extend.c
        distribution/bz_hit19.c
        distribution/bz_hit19.h
        distribution/bz_inner.c
        distribution/bz_iupac.c
        distribution/bz_iupac.h
        distribution/bz_main.c
        distribution/bz_main.h
        distribution/bz_print.c
        distribution/bz_print.h
        distribution/bz_protein.c
        distribution/bz_protein.h
        distribution/bz_site.c
        distribution/bz_site.h
        distribution/bz_table.c
        distribution/bz_table.h
        distribution/bz_weight.c
        distribution/bz_weight.h
        distribution/charvec.c
        distribution/charvec.h
        distribution/createIUPACmatrixes.c
        distribution/det-marginal-prob.c
        distribution/det-marginal-prob.h
        distribution/dna.c
        distribution/dna.h
        distribution/edit.c
        distribution/edit.h
        distribution/int_types.h
        distribution/nib.c
        distribution/nib.h
        distribution/recognize.c
        distribution/recognize.h
        distribution/seedlist.c
        distribution/seedlist.h
        distribution/seq.c
        distribution/seq.h
        distribution/util.c
        distribution/util.h
        args.c
        args.h
        astack.c
        bz_align.c
        bz_all.h
        bz_census.c
        bz_census.h
        bz_chain.c
        bz_dna.c
        bz_dna.h
        bz_extend.c
        bz_hit19.c
        bz_hit19.h
        bz_inner.c
        bz_iupac.c
        bz_iupac.h
        bz_main.c
        bz_main.h
        bz_print.c
        bz_print.h
        bz_protein.c
        bz_protein.h
        bz_site.c
        bz_site.h
        bz_table.c
        bz_table.h
        bz_weight.c
        bz_weight.h
        charvec.c
        charvec.h
        createIUPACmatrixes.c
        det-marginal-prob.c
        det-marginal-prob.h
        dna.c
        dna.h
        edit.c
        edit.h
        int_types.h
        nib.c
        nib.h
        recognize.c
        recognize.h
        seedlist.c
        seedlist.h
        seq.c
        seq.h
        util.c
        util.h)
