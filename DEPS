use_relative_paths = True

vars = {
  'github': 'https://github.com',

  'abseil_revision': '346ac9dbcfd853ecab264c1e7d08c14903a07a5a',

  'effcee_revision': '514b52ec61609744d7e587d93a7ef9b60407ab45',

  'googletest_revision': '9156d4caac880b513264ecbe0aa4746a3fead3d7',

  # Use protobufs before they gained the dependency on abseil
  'protobuf_revision': 'v21.12',

  're2_revision': 'e7aec5985072c1dbe735add802653ef4b36c231a',

  'spirv_headers_revision': '9268f3057354a2cb65991ba5f38b16d81e803692',

  'mimalloc_revision': '09a27098aa6e9286518bd9c74e6ffa7199c3f04e',
}

deps = {
  'external/abseil_cpp':
      Var('github') + '/abseil/abseil-cpp.git@' + Var('abseil_revision'),

  'external/effcee':
      Var('github') + '/google/effcee.git@' + Var('effcee_revision'),

  'external/googletest':
      Var('github') + '/google/googletest.git@' + Var('googletest_revision'),

  'external/protobuf':
      Var('github') + '/protocolbuffers/protobuf.git@' + Var('protobuf_revision'),

  'external/re2':
      Var('github') + '/google/re2.git@' + Var('re2_revision'),

  'external/spirv-headers':
      Var('github') +  '/KhronosGroup/SPIRV-Headers.git@' +
          Var('spirv_headers_revision'),

  'external/mimalloc':
      Var('github') + '/microsoft/mimalloc.git@' + Var('mimalloc_revision'),
}

