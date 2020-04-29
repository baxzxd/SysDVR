# Video format
These are the parsed sequence parameter set and picture parameter set for the grc:d stream

SPS : 0x67 0x64 0xc 0x20 0xac 0x2b 0x40 0x28 0x2 0xdd 0x35 0x1 0xd 0x1 0xe0 0x80
PPS : 0x68 0xee 0x3c 0xb0

# SPS
```
forbidden_zero_bit = 0
nal_ref_idc = 3
nal_unit_type = 7
profile_idc = 100
constrained_set0_flag = 0
constrained_set1_flag = 0
constrained_set2_flag = 0
constrained_set3_flag = 0
constrained_set4_flag = 1
reserved_zero_3bits = 4
level_idc = 32
special seq_parameter_set_id is future job
log2_max_frame_num_minus4 = 0
pic_order_cnt_type = 1
delta_pic_order_always_zero_flag = 1
offset_for_non_ref_pic  = 0
offset_for_top_to_bottom_field  = -11
num_ref_frames  = 1
gaps_in_frame_num_value_allowed_flag  = 0
pic_width_in_mbs_minus1  = 79
pic_height_in_map_units_minus1  = 44 (resolution = 1280x720)
frame_mbs_only_flag  = 1
direct_8x8_interence_flag  = 1
frame_cropping_flag  = 0
vui_parameters_present_flag  = 1

aspect_ratio_info_present_flag = 0
overscan_info_present_flag = 0
video_signal_type_present_flag = 1
video_format = 5
video_full_range_flag = 0
colour_primaries = 1
transfer_characteristics = 13
matrix_coefficients = 1
chroma_loc_info_present_flag = 1
chroma_sample_loc_type_top_field = 0
chroma_sample_loc_type_bottom_field = 0
timing_info_present_flag = 0
nal_hrd_parameters_present_flag = 0
vcl_hrd_parameters_present_flag = 0
pic_struct_present_flag = 0
bitstream_restriction_flag = 0
vBitCount = 120 vBitLength = 128
rbsp_stop_one_bit = 1
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
```
# PPS
```
forbidden_zero_bit = 0
nal_ref_idc = 3
nal_unit_type = 8
pic_parameter_set_id = 0
seq_parameter_set_id = 0
entropy_coding_mode_flag = 1
pic_order_present_flag = 0
num_slice_groups_minus1 = 0
num_ref_idx_l0_active_minus1 = 0
num_ref_idx_l1_active_minus1 = 0
weighted_pref_flag = 0
weighted_bipred_idc = 0
pic_init_qp_minus26 = 0
pic_init_qs_minus26 = 0
chroma_qp_index_offset = 0
deblocking_filter_control_present_flag = 1
constrained_intra_pred_flag = 0
redundant_pic_cnt_present_flag = 0
vBitCount = 24 vBitLength = 32
rbsp_stop_one_bit = 1
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 1
rbsp_alignment_zero_bit = 1
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
rbsp_alignment_zero_bit = 0
```