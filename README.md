# PR-repository

## Depth Estimation
<div class="page-body"><div id="54faa583-3505-4735-8cad-0eb361a4c5ba" class="collection-content"><h4 class="collection-title">Depth Estimation Paper Review</h4><table class="collection-content"><thead><tr><th><span class="icon property-icon"><svg viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesTitle"><path d="M0.637695 13.1914C1.0957 13.1914 1.32812 13 1.47852 12.5215L2.24414 10.3887H6.14746L6.90625 12.5215C7.05664 13 7.2959 13.1914 7.74707 13.1914C8.22559 13.1914 8.5332 12.9043 8.5332 12.4531C8.5332 12.2891 8.50586 12.1523 8.44434 11.9678L5.41602 3.79199C5.2041 3.21777 4.82129 2.9375 4.19922 2.9375C3.60449 2.9375 3.21484 3.21777 3.0166 3.78516L-0.0322266 12.002C-0.09375 12.1797 -0.121094 12.3232 -0.121094 12.4668C-0.121094 12.918 0.166016 13.1914 0.637695 13.1914ZM2.63379 9.12402L4.17871 4.68066H4.21973L5.76465 9.12402H2.63379ZM12.2793 13.2324C13.3115 13.2324 14.2891 12.6787 14.7129 11.8037H14.7402V12.5762C14.7471 12.9863 15.0273 13.2393 15.4238 13.2393C15.834 13.2393 16.1143 12.9795 16.1143 12.5215V8.00977C16.1143 6.49902 14.9658 5.52148 13.1543 5.52148C11.7666 5.52148 10.6592 6.08887 10.2695 6.99121C10.1943 7.15527 10.1533 7.3125 10.1533 7.46289C10.1533 7.81152 10.4062 8.04395 10.7686 8.04395C11.0215 8.04395 11.2129 7.94824 11.3496 7.73633C11.7529 6.99121 12.2861 6.65625 13.1064 6.65625C14.0977 6.65625 14.6992 7.20996 14.6992 8.1123V8.67285L12.5664 8.7959C10.7686 8.8916 9.77734 9.69824 9.77734 11.0107C9.77734 12.3369 10.8096 13.2324 12.2793 13.2324ZM12.6621 12.1387C11.8008 12.1387 11.2129 11.667 11.2129 10.9561C11.2129 10.2725 11.7598 9.82129 12.7578 9.75977L14.6992 9.62988V10.3203C14.6992 11.3457 13.7969 12.1387 12.6621 12.1387Z"></path></svg></span>이름</th><th><span class="icon property-icon"><svg viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesMultipleSelect"><path d="M1.91602 4.83789C2.44238 4.83789 2.87305 4.40723 2.87305 3.87402C2.87305 3.34766 2.44238 2.91699 1.91602 2.91699C1.38281 2.91699 0.952148 3.34766 0.952148 3.87402C0.952148 4.40723 1.38281 4.83789 1.91602 4.83789ZM5.1084 4.52344H14.3984C14.7607 4.52344 15.0479 4.23633 15.0479 3.87402C15.0479 3.51172 14.7607 3.22461 14.3984 3.22461H5.1084C4.74609 3.22461 4.45898 3.51172 4.45898 3.87402C4.45898 4.23633 4.74609 4.52344 5.1084 4.52344ZM1.91602 9.03516C2.44238 9.03516 2.87305 8.60449 2.87305 8.07129C2.87305 7.54492 2.44238 7.11426 1.91602 7.11426C1.38281 7.11426 0.952148 7.54492 0.952148 8.07129C0.952148 8.60449 1.38281 9.03516 1.91602 9.03516ZM5.1084 8.7207H14.3984C14.7607 8.7207 15.0479 8.43359 15.0479 8.07129C15.0479 7.70898 14.7607 7.42188 14.3984 7.42188H5.1084C4.74609 7.42188 4.45898 7.70898 4.45898 8.07129C4.45898 8.43359 4.74609 8.7207 5.1084 8.7207ZM1.91602 13.2324C2.44238 13.2324 2.87305 12.8018 2.87305 12.2686C2.87305 11.7422 2.44238 11.3115 1.91602 11.3115C1.38281 11.3115 0.952148 11.7422 0.952148 12.2686C0.952148 12.8018 1.38281 13.2324 1.91602 13.2324ZM5.1084 12.918H14.3984C14.7607 12.918 15.0479 12.6309 15.0479 12.2686C15.0479 11.9062 14.7607 11.6191 14.3984 11.6191H5.1084C4.74609 11.6191 4.45898 11.9062 4.45898 12.2686C4.45898 12.6309 4.74609 12.918 5.1084 12.918Z"></path></svg></span>Conference</th><th><span class="icon property-icon"><svg viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesMultipleSelect"><path d="M1.91602 4.83789C2.44238 4.83789 2.87305 4.40723 2.87305 3.87402C2.87305 3.34766 2.44238 2.91699 1.91602 2.91699C1.38281 2.91699 0.952148 3.34766 0.952148 3.87402C0.952148 4.40723 1.38281 4.83789 1.91602 4.83789ZM5.1084 4.52344H14.3984C14.7607 4.52344 15.0479 4.23633 15.0479 3.87402C15.0479 3.51172 14.7607 3.22461 14.3984 3.22461H5.1084C4.74609 3.22461 4.45898 3.51172 4.45898 3.87402C4.45898 4.23633 4.74609 4.52344 5.1084 4.52344ZM1.91602 9.03516C2.44238 9.03516 2.87305 8.60449 2.87305 8.07129C2.87305 7.54492 2.44238 7.11426 1.91602 7.11426C1.38281 7.11426 0.952148 7.54492 0.952148 8.07129C0.952148 8.60449 1.38281 9.03516 1.91602 9.03516ZM5.1084 8.7207H14.3984C14.7607 8.7207 15.0479 8.43359 15.0479 8.07129C15.0479 7.70898 14.7607 7.42188 14.3984 7.42188H5.1084C4.74609 7.42188 4.45898 7.70898 4.45898 8.07129C4.45898 8.43359 4.74609 8.7207 5.1084 8.7207ZM1.91602 13.2324C2.44238 13.2324 2.87305 12.8018 2.87305 12.2686C2.87305 11.7422 2.44238 11.3115 1.91602 11.3115C1.38281 11.3115 0.952148 11.7422 0.952148 12.2686C0.952148 12.8018 1.38281 13.2324 1.91602 13.2324ZM5.1084 12.918H14.3984C14.7607 12.918 15.0479 12.6309 15.0479 12.2686C15.0479 11.9062 14.7607 11.6191 14.3984 11.6191H5.1084C4.74609 11.6191 4.45898 11.9062 4.45898 12.2686C4.45898 12.6309 4.74609 12.918 5.1084 12.918Z"></path></svg></span>Year</th><th><span class="icon property-icon"><svg viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesUrl"><path d="M7.69922 10.8945L8.73828 9.84863C7.91797 9.77344 7.34375 9.51367 6.91992 9.08984C5.76465 7.93457 5.76465 6.29395 6.91309 5.14551L9.18262 2.87598C10.3379 1.7207 11.9717 1.7207 13.127 2.87598C14.2891 4.04492 14.2822 5.67188 13.1338 6.82031L11.958 7.99609C12.1768 8.49512 12.2451 9.10352 12.1289 9.62988L14.0908 7.6748C15.7725 6 15.7793 3.62109 14.084 1.92578C12.3887 0.223633 10.0098 0.237305 8.33496 1.91211L5.95605 4.29785C4.28125 5.97266 4.26758 8.35156 5.96289 10.0469C6.36621 10.4434 6.90625 10.7441 7.69922 10.8945ZM8.30078 5.13184L7.26855 6.17773C8.08203 6.25293 8.66309 6.51953 9.08008 6.93652C10.2422 8.09863 10.2422 9.73242 9.08691 10.8809L6.81738 13.1504C5.66211 14.3057 4.03516 14.3057 2.87305 13.1504C1.71094 11.9883 1.71777 10.3545 2.87305 9.20605L4.04199 8.03027C3.83008 7.53125 3.75488 6.92969 3.87109 6.39648L1.91602 8.35156C0.234375 10.0264 0.227539 12.4121 1.92285 14.1074C3.61816 15.8027 5.99707 15.7891 7.67188 14.1143L10.0439 11.7354C11.7256 10.0537 11.7324 7.6748 10.0371 5.98633C9.64062 5.58301 9.10059 5.28223 8.30078 5.13184Z"></path></svg></span>related URL</th><th><span class="icon property-icon"><svg viewBox="0 0 16 16" style="width:14px;height:14px;display:block;fill:rgba(55, 53, 47, 0.45);flex-shrink:0;-webkit-backface-visibility:hidden" class="typesText"><path d="M1.56738 3.25879H14.4258C14.7676 3.25879 15.0479 2.97852 15.0479 2.63672C15.0479 2.29492 14.7744 2.02148 14.4258 2.02148H1.56738C1.21875 2.02148 0.952148 2.29492 0.952148 2.63672C0.952148 2.97852 1.22559 3.25879 1.56738 3.25879ZM1.56738 6.84082H14.4258C14.7676 6.84082 15.0479 6.56055 15.0479 6.21875C15.0479 5.87695 14.7744 5.60352 14.4258 5.60352H1.56738C1.21875 5.60352 0.952148 5.87695 0.952148 6.21875C0.952148 6.56055 1.22559 6.84082 1.56738 6.84082ZM1.56738 10.4229H14.4258C14.7676 10.4229 15.0479 10.1426 15.0479 9.80078C15.0479 9.45898 14.7744 9.18555 14.4258 9.18555H1.56738C1.21875 9.18555 0.952148 9.45898 0.952148 9.80078C0.952148 10.1426 1.22559 10.4229 1.56738 10.4229ZM1.56738 14.0049H8.75879C9.10059 14.0049 9.38086 13.7246 9.38086 13.3828C9.38086 13.041 9.10742 12.7676 8.75879 12.7676H1.56738C1.21875 12.7676 0.952148 13.041 0.952148 13.3828C0.952148 13.7246 1.22559 14.0049 1.56738 14.0049Z"></path></svg></span>Title</th></tr></thead><tbody><tr id="9df82c3e-62b8-4f89-9f4d-524dab38edf2"><td class="cell-title"><a href="https://www.notion.so/MonoDepth-9df82c3e62b84f899f4d524dab38edf2">MonoDepth</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-pink">AAAI</span></td><td class="cell-reNG"><span class="selected-value select-value-color-blue">2017</span></td><td class="cell-zy~D"><a href="https://github.com/mrharicot/monodepth" class="url-value">https://github.com/mrharicot/monodepth</a></td><td class="cell-KSlL"><strong>Unsupervised Monocular Depth Estimation with Left-Right Consistency</strong></td></tr><tr id="537cf5fd-7481-43bb-b762-5838549474c7"><td class="cell-title"><a href="https://www.notion.so/MonoDepth2-537cf5fd748143bbb7625838549474c7">MonoDepth2</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-blue">ICCV</span></td><td class="cell-reNG"><span class="selected-value select-value-color-gray">2019</span></td><td class="cell-zy~D"><a href="https://github.com/nianticlabs/monodepth2" class="url-value">https://github.com/nianticlabs/monodepth2</a></td><td class="cell-KSlL"></td></tr><tr id="bb14cc5c-8598-473e-974c-38deaed894b3"><td class="cell-title"><a href="https://www.notion.so/DepthNet-bb14cc5c8598473e974c38deaed894b3">DepthNet</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-default">CVPR</span></td><td class="cell-reNG"><span class="selected-value select-value-color-purple">2018</span></td><td class="cell-zy~D"><a href="https://ieeexplore.ieee.org/document/8575528" class="url-value">https://ieeexplore.ieee.org/document/8575528</a></td><td class="cell-KSlL"></td></tr><tr id="2a2aedb3-67c8-4c9b-82e9-1bcf7c9956ee"><td class="cell-title"><a href="https://www.notion.so/S2R-DepthNet-2a2aedb367c84c9b82e91bcf7c9956ee">S2R-DepthNet</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-default">CVPR</span></td><td class="cell-reNG"><span class="selected-value select-value-color-brown">2021</span></td><td class="cell-zy~D"></td><td class="cell-KSlL"></td></tr><tr id="53ff60eb-dd09-41c3-b558-6a6132e97927"><td class="cell-title"><a href="https://www.notion.so/ADDS-DepthNet-53ff60ebdd0941c3b5586a6132e97927">ADDS-DepthNet</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-blue">ICCV</span></td><td class="cell-reNG"><span class="selected-value select-value-color-brown">2021</span></td><td class="cell-zy~D"></td><td class="cell-KSlL"></td></tr><tr id="82c910b2-8fae-42e4-bf6c-b769fb89a9ee"><td class="cell-title"><a href="https://www.notion.so/FastDepth-82c910b28fae42e4bf6cb769fb89a9ee">FastDepth</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-gray">ICRA</span></td><td class="cell-reNG"><span class="selected-value select-value-color-gray">2019</span></td><td class="cell-zy~D"></td><td class="cell-KSlL"></td></tr><tr id="628c2034-f822-4b31-b03b-55a9e9a4f85e"><td class="cell-title"><a href="https://www.notion.so/DeMoN-628c2034f8224b31b03b55a9e9a4f85e">DeMoN</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-default">CVPR</span></td><td class="cell-reNG"><span class="selected-value select-value-color-blue">2017</span></td><td class="cell-zy~D"><a href="https://github.com/lmb-freiburg/demon" class="url-value">https://github.com/lmb-freiburg/demon</a></td><td class="cell-KSlL"></td></tr><tr id="a5229cf6-0ea1-4777-aed1-651e43901d9e"><td class="cell-title"><a href="https://www.notion.so/SfM-Net-a5229cf60ea14777aed1651e43901d9e">SfM-Net</a></td><td class="cell-_j;F"></td><td class="cell-reNG"><span class="selected-value select-value-color-blue">2017</span></td><td class="cell-zy~D"><a href="https://arxiv.org/abs/1704.07804" class="url-value">https://arxiv.org/abs/1704.07804</a></td><td class="cell-KSlL"></td></tr><tr id="0d8f2f02-756d-4af2-809b-706fea2ba880"><td class="cell-title"><a href="https://www.notion.so/DeepSfM-0d8f2f02756d4af2809b706fea2ba880">DeepSfM</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-red">ECCV</span></td><td class="cell-reNG"></td><td class="cell-zy~D"><a href="https://github.com/weixk2015/DeepSFM" class="url-value">https://github.com/weixk2015/DeepSFM</a></td><td class="cell-KSlL"></td></tr><tr id="438e70a9-c7e9-4d67-a996-70738cf09664"><td class="cell-title"><a href="https://www.notion.so/DenseDepth-438e70a9c7e94d67a99670738cf09664">DenseDepth</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-orange">arXiv</span></td><td class="cell-reNG"><span class="selected-value select-value-color-purple">2018</span></td><td class="cell-zy~D"><a href="https://github.com/ialhashim/DenseDepth" class="url-value">https://github.com/ialhashim/DenseDepth</a></td><td class="cell-KSlL"></td></tr><tr id="a221864f-6af8-4756-971d-38fa858ec65c"><td class="cell-title"><a href="https://www.notion.so/Multi-View-Stereo-MVS-a221864f6af84756971d38fa858ec65c">Multi-View Stereo (MVS)</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-pink">😎AWESOME</span></td><td class="cell-reNG"></td><td class="cell-zy~D"><a href="https://github.com/walsvid/Awesome-MVS" class="url-value">https://github.com/walsvid/Awesome-MVS</a></td><td class="cell-KSlL"></td></tr><tr id="b02ba5d2-4971-49a3-a0d2-a460d510346d"><td class="cell-title"><a href="https://www.notion.so/Attention-guided-Depth-Estimation-b02ba5d2497149a3a0d2a460d510346d">Attention-guided Depth Estimation</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-default">CVPR</span></td><td class="cell-reNG"><span class="selected-value select-value-color-purple">2018</span></td><td class="cell-zy~D"><a href="https://github.com/danxuhk/StructuredAttentionDepthEstimation" class="url-value">https://github.com/danxuhk/StructuredAttentionDepthEstimation</a></td><td class="cell-KSlL"></td></tr><tr id="8d286122-24a4-4937-8f9a-4ed7d3faa196"><td class="cell-title"><a href="https://www.notion.so/Sparse-to-Dense-8d28612224a449378f9a4ed7d3faa196">Sparse-to-Dense</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-gray">ICRA</span></td><td class="cell-reNG"><span class="selected-value select-value-color-purple">2018</span></td><td class="cell-zy~D"><a href="https://github.com/fangchangma/sparse-to-dense" class="url-value">https://github.com/fangchangma/sparse-to-dense</a></td><td class="cell-KSlL"></td></tr><tr id="7644cfdd-e8a2-4529-b7c4-7475dd788814"><td class="cell-title"><a href="https://www.notion.so/PlaneRCNN-7644cfdde8a24529b7c47475dd788814">PlaneRCNN</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-default">CVPR</span></td><td class="cell-reNG"><span class="selected-value select-value-color-gray">2019</span></td><td class="cell-zy~D"><a href="https://github.com/NVlabs/planercnn" class="url-value">https://github.com/NVlabs/planercnn</a></td><td class="cell-KSlL"></td></tr><tr id="019c8f19-3f6e-4dd7-a1af-6fe9ff18f6df"><td class="cell-title"><a href="https://www.notion.so/BTS-019c8f193f6e4dd7a1af6fe9ff18f6df">BTS</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-orange">arXiv</span></td><td class="cell-reNG"><span class="selected-value select-value-color-gray">2019</span></td><td class="cell-zy~D"><a href="https://github.com/cleinc/bts" class="url-value">https://github.com/cleinc/bts</a></td><td class="cell-KSlL"></td></tr><tr id="13969475-cd94-4bcd-8084-821c43d1f2f0"><td class="cell-title"><a href="https://www.notion.so/TriDepth-13969475cd944bcd8084821c43d1f2f0">TriDepth</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-brown">WACV</span></td><td class="cell-reNG"><span class="selected-value select-value-color-pink">2023</span></td><td class="cell-zy~D"><a href="https://github.com/xingyuuchen/tri-depth" class="url-value">https://github.com/xingyuuchen/tri-depth</a></td><td class="cell-KSlL"></td></tr><tr id="110f4172-6bb2-44d2-a009-28441033a53e"><td class="cell-title"><a href="https://www.notion.so/RoutedFusion-110f41726bb244d2a00928441033a53e">RoutedFusion</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-default">CVPR</span></td><td class="cell-reNG"><span class="selected-value select-value-color-gray">2020</span></td><td class="cell-zy~D"><a href="https://github.com/weders/RoutedFusion" class="url-value">https://github.com/weders/RoutedFusion</a></td><td class="cell-KSlL"></td></tr><tr id="844319c8-8390-4fa1-af4b-52c426dc0191"><td class="cell-title"><a href="https://www.notion.so/IronDepth-844319c883904fa1af4b52c426dc0191">IronDepth</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-pink">BMVC</span></td><td class="cell-reNG"><span class="selected-value select-value-color-green">2022</span></td><td class="cell-zy~D"><a href="https://github.com/baegwangbin/IronDepth" class="url-value">https://github.com/baegwangbin/IronDepth</a></td><td class="cell-KSlL"></td></tr><tr id="afb8447b-37ec-4daa-a17c-1e68733526c2"><td class="cell-title"><a href="https://www.notion.so/DiffusionDepth-afb8447b37ec4daaa17c1e68733526c2">DiffusionDepth</a></td><td class="cell-_j;F"></td><td class="cell-reNG"></td><td class="cell-zy~D"><a href="https://github.com/duanyiqun/DiffusionDepth" class="url-value">https://github.com/duanyiqun/DiffusionDepth</a></td><td class="cell-KSlL"></td></tr><tr id="744b31d0-1402-4df2-a25e-14d4cc2cda54"><td class="cell-title"><a href="https://www.notion.so/360-Depth-Estimation-744b31d014024df2a25e14d4cc2cda54">360 Depth Estimation</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-pink">😎AWESOME</span></td><td class="cell-reNG"></td><td class="cell-zy~D"><a href="https://github.com/bkhanal-11/awesome-360-depth-estimation" class="url-value">https://github.com/bkhanal-11/awesome-360-depth-estimation</a></td><td class="cell-KSlL"></td></tr><tr id="06c5ad36-665b-4c31-889b-bc0552b6ec49"><td class="cell-title"><a href="https://www.notion.so/Depth-06c5ad36665b4c31889bbc0552b6ec49">Depth</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-pink">😎AWESOME</span></td><td class="cell-reNG"><span class="selected-value select-value-color-gray">2019</span></td><td class="cell-zy~D"><a href="https://github.com/scott89/awesome-depth" class="url-value">https://github.com/scott89/awesome-depth</a></td><td class="cell-KSlL"></td></tr><tr id="fdb4cbca-c295-4315-9c27-e1fde05ef106"><td class="cell-title"><a href="https://www.notion.so/Monocular-Depth-Est-fdb4cbcac29543159c27e1fde05ef106">Monocular-Depth-Est.</a></td><td class="cell-_j;F"><span class="selected-value select-value-color-pink">😎AWESOME</span></td><td class="cell-reNG"><span class="selected-value select-value-color-brown">2021</span></td><td class="cell-zy~D"><a href="https://github.com/scott89/awesome-depth" class="url-value">https://github.com/scott89/awesome-depth</a></td><td class="cell-KSlL"></td></tr></tbody></table></div><p id="a9a93f12-b091-4b17-90ac-6c112aa97675" class=""></p></div>

## Image Segmentation
...

## Object Detection - 2D
PR : CNN, R-CNN Family (RCNN / Fast-RCNN / Faster-RCNN / Masked-RCNN), YOLO Family (YOLO, YOLOv3, YOLOv5), etc.

## Object Detection - 3D
PR : PointNet, VoxelNet, Point-Pillars, VoxelNeXt, CenterPoint, ComplexYOLO, etc.

## Transformer
PR : Transformer, Vision-Transformer

