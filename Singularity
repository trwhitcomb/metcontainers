Bootstrap: docker
From: dtcenter/met:latest

%post
    yum -y install R

%apprun ascii2nc
    exec /usr/local/bin/ascii2nc $@

%apphelp ascii2nc
    Run the MET ascii2nc command.

%apprun ensemble_stat
    exec /usr/local/bin/ensemble_stat $@

%apphelp ensemble_stat
    Run the MET ensemble_stat command.

%apprun gen_vx_mask
    exec /usr/local/bin/gen_vx_mask $@

%apphelp gen_vx_mask
    Run the MET gen_vx_mask command.

%apprun gis_dump_dbf
    exec /usr/local/bin/gis_dump_dbf $@

%apphelp gis_dump_dbf
    Run the MET gis_dump_dbf command.

%apprun gis_dump_shp
    exec /usr/local/bin/gis_dump_shp $@

%apphelp gis_dump_shp
    Run the MET gis_dump_shp command.

%apprun gis_dump_shx
    exec /usr/local/bin/gis_dump_shx $@

%apphelp gis_dump_shx
    Run the MET gis_dump_shx command.

%apprun grid_stat
    exec /usr/local/bin/grid_stat $@

%apphelp grid_stat
    Run the MET grid_stat command.

%apprun gsid2mpr
    exec /usr/local/bin/gsid2mpr $@

%apphelp gsid2mpr
    Run the MET gsid2mpr command.

%apprun gsidens2orank
    exec /usr/local/bin/gsidens2orank $@

%apphelp gsidens2orank
    Run the MET gsidens2orank command.

%apprun lidar2nc
    exec /usr/local/bin/lidar2nc $@

%apphelp lidar2nc
    Run the MET lidar2nc command.

%apprun madis2nc
    exec /usr/local/bin/madis2nc $@

%apphelp madis2nc
    Run the MET madis2nc command.

%apprun mode
    exec /usr/local/bin/mode $@

%apphelp mode
    Run the MET mode command.

%apprun mode_analysis
    exec /usr/local/bin/mode_analysis $@

%apphelp mode_analysis
    Run the MET mode_analysis command.

%apprun modis_regrid
    exec /usr/local/bin/modis_regrid $@

%apphelp modis_regrid
    Run the MET modis_regrid command.

%apprun mtd
    exec /usr/local/bin/mtd $@

%apphelp mtd
    Run the MET mtd command.

%apprun nc-config
    exec /usr/local/bin/nc-config $@

%apphelp nc-config
    Run the MET nc-config command.

%apprun nccopy
    exec /usr/local/bin/nccopy $@

%apphelp nccopy
    Run the MET nccopy command.

%apprun ncdump
    exec /usr/local/bin/ncdump $@

%apphelp ncdump
    Run the MET ncdump command.

%apprun ncgen
    exec /usr/local/bin/ncgen $@

%apphelp ncgen
    Run the MET ncgen command.

%apprun ncgen3
    exec /usr/local/bin/ncgen3 $@

%apphelp ncgen3
    Run the MET ncgen3 command.

%apprun ncxx4-config
    exec /usr/local/bin/ncxx4-config $@

%apphelp ncxx4-config
    Run the MET ncxx4-config command.

%apprun pb2nc
    exec /usr/local/bin/pb2nc $@

%apphelp pb2nc
    Run the MET pb2nc command.

%apprun pcp_combine
    exec /usr/local/bin/pcp_combine $@

%apphelp pcp_combine
    Run the MET pcp_combine command.

%apprun plot_data_plane
    exec /usr/local/bin/plot_data_plane $@

%apphelp plot_data_plane
    Run the MET plot_data_plane command.

%apprun plot_mode_field
    exec /usr/local/bin/plot_mode_field $@

%apphelp plot_mode_field
    Run the MET plot_mode_field command.

%apprun plot_point_obs
    exec /usr/local/bin/plot_point_obs $@

%apphelp plot_point_obs
    Run the MET plot_point_obs command.

%apprun point_stat
    exec /usr/local/bin/point_stat $@

%apphelp point_stat
    Run the MET point_stat command.

%apprun regrid_data_plane
    exec /usr/local/bin/regrid_data_plane $@

%apphelp regrid_data_plane
    Run the MET regrid_data_plane command.

%apprun series_analysis
    exec /usr/local/bin/series_analysis $@

%apphelp series_analysis
    Run the MET series_analysis command.

%apprun shift_data_plane
    exec /usr/local/bin/shift_data_plane $@

%apphelp shift_data_plane
    Run the MET shift_data_plane command.

%apprun stat_analysis
    exec /usr/local/bin/stat_analysis $@

%apphelp stat_analysis
    Run the MET stat_analysis command.

%apprun tc_dland
    exec /usr/local/bin/tc_dland $@

%apphelp tc_dland
    Run the MET tc_dland command.

%apprun tc_pairs
    exec /usr/local/bin/tc_pairs $@

%apphelp tc_pairs
    Run the MET tc_pairs command.

%apprun tc_stat
    exec /usr/local/bin/tc_stat $@

%apphelp tc_stat
    Run the MET tc_stat command.

%apprun wavelet_stat
    exec /usr/local/bin/wavelet_stat $@

%apphelp wavelet_stat
    Run the MET wavelet_stat command.

%apprun wwmca_plot
    exec /usr/local/bin/wwmca_plot $@

%apphelp wwmca_plot
    Run the MET wwmca_plot command.

%apprun wwmca_regrid
    exec /usr/local/bin/wwmca_regrid $@

%apphelp wwmca_regrid
    Run the MET wwmca_regrid command.
#ensemble_stat
#gen_vx_mask
#gis_dump_dbf
#gis_dump_shp
#gis_dump_shx
#grid_stat
#gsid2mpr
#gsidens2orank
#lidar2nc
#madis2nc
#mode
#mode_analysis
#modis_regrid
#mtd
#nc-config
#nccopy
#ncdump
#ncgen
#ncgen3
#ncxx4-config
#pb2nc
#pcp_combine
#plot_data_plane
#plot_mode_field
#plot_point_obs
#point_stat
#regrid_data_plane
#series_analysis
#shift_data_plane
#stat_analysis
#tc_dland
#tc_pairs
#tc_stat
#wavelet_stat
#wwmca_plot
#wwmca_regrid

#%post
#    apt-get update && apt-get --no-install-recommends -y install \
#        at \
#        build-essential \
#        less \
#        git \
#        graphviz graphviz-dev libgraphviz-dev \
#        heirloom-mailx \
#        language-pack-en-base
#        less \
#        pkg-config \
#        python-gtk2-dev \
#        python-pip \
#        python-wheel \
#        python-pygraphviz \
#        python python-dev python-pip \
#        python-setuptools \
#        sqlite \
#        time \
#        texlive-latex-base \
#        texlive-latex-extra
#    pip install pycodestyle pyopenssl
#    dpkg-reconfigure locales
#    mkdir -p /opt
#    cd /opt
#    git clone --branch 7.8.1 https://github.com/cylc/cylc.git
#    cd cylc
#    make
#
#%environment
#    export LC_ALL="en.utf-8"
#
#%runscript
#    exec /opt/cylc/bin/cylc $@
