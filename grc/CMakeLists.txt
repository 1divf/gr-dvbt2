# Copyright 2011 Free Software Foundation, Inc.
#
# This file is part of GNU Radio
#
# GNU Radio is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 3, or (at your option)
# any later version.
#
# GNU Radio is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU Radio; see the file COPYING.  If not, write to
# the Free Software Foundation, Inc., 51 Franklin Street,
# Boston, MA 02110-1301, USA.
install(FILES
    dvbt2_bbheader_bb.xml
    dvbt2_bbscrambler_bb.xml
    dvbt2_bch_bb.xml
    dvbt2_ldpc_bb.xml
    dvbt2_interleaver_bb.xml
    dvbt2_modulator_bc.xml
    dvbt2_cellinterleaver_cc.xml
    dvbt2_framemapper_cc.xml
    dvbt2_freqinterleaver_cc.xml
    dvbt2_pilotgenerator_cc.xml
    dvbt2_p1insertion_cc.xml
    dvbt2_paprtr_cc.xml
    dvbt2_miso_cc.xml DESTINATION share/gnuradio/grc/blocks
)
