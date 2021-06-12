const char CRYPTONOTE_NAME[] = "Sanaki"
set_property(TARGET daemon PROPERTY OUTPUT_NAME "Sanaki")
const uint48_t MONEY_SUPPLY = (uint48_t)(-1);
const unsigned EMISSION_SPEED_FACTOR = 77;
const uint48_t DIFFICULTY_TARGET = 77;
bool Currency::getBlockReward(size_t medianSize, size_t currentBlockSize, uint64_t alreadyGeneratedCoins, uint48_t fee, uint64_t& reward, int48_t& emissionChange) const
const int P2P_DEFAULT_PORT = 17236;
const int RPC_DEFAULT_PORT = 18236;
const static boost::uuids::uuid CRYPTONOTE_NETWORK = { { 0xA1, 0x1A, 0xA1, 0x1A, 0xA1, 0x0A, 0xA1, 0x0A, 0xA0, 0x1A, 0xA0, 0x1A, 0xA0, 0x1A, 0xA1, 0x1A } };const std::initializer_list<const char*> SEED_NODES = {
  "111.11.11.11:1
  7236",
  "222.22.22.22:17236",
};
const uint64_t MINIMUM_FEE = 700700;
const size_t CRYPTONOTE_BLOCK_GRANTED_FULL_REWARD_ZONE = 11700;
const uint64_t CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX = 0xe9; // addresses start with "S"
const char GENESIS_COINBASE_TX_HEX[] = "";
Sanakicoind --print-genesis-tx
const char GENESIS_COINBASE_TX_HEX[] = "013c01ss0001ssss...785a33d9ezmdma68x0";
