# Overview
This repository contains benchmarks compiled by ParserHawk. Below is a mapping of program names to their respective code.

## Program Mapping

| Program Name                                        | Description |
|-----------------------------------------------------|-------------|
| `Parse Ethernet`                                   | parse_ethernet/parse_ethernet.p4 |
| `+ R1`                                            | parse_ethernet/parse_ethernet_m1.p4 |
| `- R3`                                            | parse_ethernet/parse_ethernet_m2.p4 |
| `+ R2`                                            | parse_ethernet/parse_ethernet_m3.p4 |
| `Parse ICMP`                                      | parse_icmp/parse_icmp.p4 |
| `+ R5`                                            | parse_icmp/parse_icmp_m1.p4 |
| `- R3`                                            | parse_icmp/parse_icmp_m2.p4 |
| `Parse MPLS`                                      | loop/loop.p4 |
| `+ Unroll loop`                                   | loop/loop_m1.p4 |
| `- R1`                                            | loop/loop_m2.p4 |
| `+ R1`                                            | loop/loop_m3.p4 |
| `Large tran key`                                  | large_tran_key/large_tran_key.p4 |
| `+ R4`                                            | large_tran_key/large_tran_key_m1.p4 |
| `+ R1 + R4`                                       | large_tran_key/large_tran_key_m2.p4 |
| `+ R3 + R4`                                       | large_tran_key/large_tran_key_m3.p4 |
| `Multi-key (same pkt field)`                   | multi_key_same_field/multi_key_same_field.p4 |
| `- R5`                                            | multi_key_same_field/multi_key_same_field_m1.p4 |
| `- R5 - R3`                                       | multi_key_same_field/multi_key_same_field_m2.p4 |
| `Multi-key (different pkt field)`            | multi_key_diff_field/multi_key_diff_field.p4 |
| `+ R5`                                        | multi_key_diff_field/multi_key_diff_field_m1.p4 |
| `- R5`                                            | multi_key_diff_field/multi_key_diff_field_m2.p4 |
| `Pure Extraction states`                          | pure_extraction/pure_extraction.p4 |
| `+ State merging`                                 | pure_extraction/pure_extraction_m1.p4 |


