ipa_common-objs := ipa_api.o ipa_rm.o ipa_rm_dependency_graph.o ipa_rm_peers_list.o ipa_rm_resource.o ipa_rm_inactivity_timer.o

obj-$(CONFIG_IPA) += ipa_v2/ ipa_clients/ $(ipa_common-objs)
obj-$(CONFIG_IPA3) += ipa_v3/ ipa_clients/ $(ipa_common-objs)
obj-$(CONFIG_IPA_UT) += test/

