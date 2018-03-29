# This is _NOT_ the library release version, it's an API version.
# Please read Chapter 6 "Library interface versions" of the libtool
# documentation before making any modification
LIBVERSION=1:0:0

AM_CPPFLAGS = $(all_includes) -I$(top_srcdir)/include/asn1c
AM_CFLAGS = -fPIC -Wall $(LIBTALLOC_CFLAGS)
if BUILD_DEBUG
AM_CFLAGS += -DEMIT_ASN_DEBUG=1
endif

lib_LTLIBRARIES = libasn1c.la

libasn1c_la_LDFLAGS = $(LIBTALLOC_LIBS) -lm
libasn1c_la_SOURCES = ANY.c asn_application.c asn_bit_data.c asn_codecs_prim.c asn_internal.c asn_random_fill.c asn_SEQUENCE_OF.c asn_SET_OF.c ber_decoder.c ber_tlv_length.c ber_tlv_tag.c BIT_STRING.c BIT_STRING_oer.c BMPString.c BOOLEAN.c constraints.c constr_CHOICE.c constr_CHOICE_oer.c constr_SEQUENCE.c constr_SEQUENCE_oer.c constr_SEQUENCE_OF.c constr_SET.c constr_SET_OF.c constr_SET_OF_oer.c constr_TYPE.c der_encoder.c ENUMERATED.c GeneralizedTime.c GeneralString.c GraphicString.c IA5String.c INTEGER.c INTEGER_oer.c ISO646String.c NativeEnumerated.c NativeEnumerated_oer.c NativeInteger.c NativeInteger_oer.c NativeReal.c NULL.c NumericString.c ObjectDescriptor.c OBJECT_IDENTIFIER.c OCTET_STRING.c OCTET_STRING_oer.c oer_decoder.c oer_encoder.c oer_support.c OPEN_TYPE.c OPEN_TYPE_oer.c per_decoder.c per_encoder.c per_opentype.c per_support.c PrintableString.c REAL.c RELATIVE-OID.c T61String.c TeletexString.c UniversalString.c UTCTime.c UTF8String.c VideotexString.c VisibleString.c xer_decoder.c xer_encoder.c xer_support.c asn1helpers.c
