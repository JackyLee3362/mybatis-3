```sh
.
└── org
    └── apache
        └── ibatis
            ├── autoconstructor
            │   ├── AnnotatedSubject
            │   ├── AutoConstructorMapper
            │   ├── AutoConstructorTest
            │   ├── BadAnnotatedSubject
            │   ├── BadSubject
            │   ├── ExtensiveSubject
            │   └── PrimitiveSubject
            ├── BaseDataTest
            ├── binding
            │   ├── BindingTest
            │   ├── BoundAuthorMapper
            │   ├── BoundBlogMapper
            │   ├── BoundBlogSql
            │   ├── FlushTest
            │   ├── MapperMethodParamTest
            │   ├── MapperWithOneAndMany
            │   ├── MissingNamespaceMapper
            │   ├── WrongMapperTest
            │   ├── WrongNamespaceMapper
            │   └── WrongNamespacesTest
            ├── builder
            │   ├── AnnotationMapperBuilderTest
            │   ├── CachedAuthorMapper
            │   ├── CustomLongTypeHandler
            │   ├── CustomObjectWrapperFactory
            │   ├── CustomReflectorFactory
            │   ├── CustomStringTypeHandler
            │   ├── ExampleObjectFactory
            │   ├── ExamplePlugin
            │   ├── mapper
            │   │   └── CustomMapper
            │   ├── ParameterExpressionTest
            │   ├── ResultMappingConstructorResolverTest
            │   ├── SqlSourceBuilderTest
            │   ├── typehandler
            │   │   └── CustomIntegerTypeHandler
            │   ├── xml
            │   │   └── dynamic
            │   │       ├── DynamicSqlSourceTest
            │   │       └── ExpressionEvaluatorTest
            │   ├── XmlConfigBuilderTest
            │   ├── XmlMapperBuilderTest
            │   └── xsd
            │       ├── CachedAuthorMapper
            │       ├── XmlConfigBuilderTest
            │       └── XmlMapperBuilderTest
            ├── cache
            │   ├── BaseCacheTest
            │   ├── CacheKeyTest
            │   ├── FifoCacheTest
            │   ├── LruCacheTest
            │   ├── PerpetualCacheTest
            │   ├── ScheduledCacheTest
            │   ├── SerializedCacheTest
            │   ├── SoftCacheTest
            │   ├── SuperCacheTest
            │   └── WeakCacheTest
            ├── cursor
            │   └── defaults
            │       └── DefaultCursorTest
            ├── databases
            │   └── blog
            │       └── StoredProcedures
            ├── datasource
            │   ├── jndi
            │   │   └── JndiDataSourceFactoryTest
            │   ├── pooled
            │   │   ├── MysqlTimeoutTest
            │   │   └── PooledDataSourceTest
            │   └── unpooled
            │       ├── NetworkTimeoutTest
            │       └── UnpooledDataSourceTest
            ├── domain
            │   ├── blog
            │   │   ├── Author
            │   │   ├── Blog
            │   │   ├── BlogLite
            │   │   ├── Comment
            │   │   ├── ComplexImmutableAuthor
            │   │   ├── ComplexImmutableAuthorId
            │   │   ├── DraftPost
            │   │   ├── immutable
            │   │   │   ├── ImmutableAuthor
            │   │   │   ├── ImmutableBlog
            │   │   │   ├── ImmutableComment
            │   │   │   ├── ImmutablePost
            │   │   │   └── ImmutableTag
            │   │   ├── mappers
            │   │   │   ├── AuthorMapper
            │   │   │   ├── AuthorMapperWithMultipleHandlers
            │   │   │   ├── AuthorMapperWithRowBounds
            │   │   │   ├── BlogMapper
            │   │   │   ├── CopyOfAuthorMapper
            │   │   │   └── NestedBlogMapper
            │   │   ├── Post
            │   │   ├── PostLite
            │   │   ├── PostLiteId
            │   │   ├── Section
            │   │   └── Tag
            │   ├── jpetstore
            │   │   ├── Account
            │   │   ├── Cart
            │   │   ├── CartItem
            │   │   ├── Category
            │   │   ├── Item
            │   │   ├── LineItem
            │   │   ├── Order
            │   │   ├── Product
            │   │   └── Sequence
            │   └── misc
            │       ├── CustomBeanWrapper
            │       ├── CustomBeanWrapperFactory
            │       ├── Employee
            │       ├── generics
            │       │   ├── GenericAbstract
            │       │   ├── GenericConcrete
            │       │   ├── GenericInterface
            │       │   └── GenericSubclass
            │       └── RichType
            ├── exceptions
            │   └── GeneralExceptionsTest
            ├── executor
            │   ├── BaseExecutorTest
            │   ├── BatchExecutorTest
            │   ├── CachingBatchExecutorTest
            │   ├── CachingReuseExecutorTest
            │   ├── CachingSimpleExecutorTest
            │   ├── ErrorContextTest
            │   ├── ExecutorTestHelper
            │   ├── loader
            │   │   ├── CglibProxyTest
            │   │   ├── JavassistProxyTest
            │   │   └── SerializableProxyTest
            │   ├── ResultExtractorTest
            │   ├── resultset
            │   │   ├── DefaultResultSetHandlerTest
            │   │   └── DefaultResultSetHandlerTest2
            │   ├── ReuseExecutorTest
            │   └── statement
            │       └── BaseStatementHandlerTest
            ├── immutable
            │   ├── ImmutableBlogMapper
            │   └── ImmutableConstructorTest
            ├── io
            │   ├── ClassLoaderWrapperTest
            │   ├── ExternalResourcesTest
            │   ├── ResolverUtilTest
            │   ├── ResourcesTest
            │   └── VFSTest
            ├── jdbc
            │   ├── NullTest
            │   ├── PooledDataSourceTest
            │   ├── ScriptRunnerTest
            │   ├── SelectBuilderTest
            │   ├── SqlBuilderTest
            │   ├── SqlRunnerTest
            │   └── SQLTest
            ├── logging
            │   ├── jdbc
            │   │   ├── BaseJdbcLoggerTest
            │   │   ├── ConnectionLoggerTest
            │   │   ├── PreparedStatementLoggerTest
            │   │   ├── ResultSetLoggerTest
            │   │   └── StatementLoggerTest
            │   └── LogFactoryTest
            ├── mapping
            │   ├── BoundSqlTest
            │   ├── CacheBuilderTest
            │   ├── ResultMappingTest
            │   └── VendorDatabaseIdProviderTest
            ├── parsing
            │   ├── GenericTokenParserTest
            │   ├── PropertyParserTest
            │   ├── XNodeTest
            │   └── XPathParserTest
            ├── plugin
            │   ├── Mapper
            │   └── PluginTest
            ├── reflection
            │   ├── ArrayUtilTest
            │   ├── ExceptionUtilTest
            │   ├── factory
            │   │   ├── DefaultObjectFactoryTest
            │   │   └── TestClass
            │   ├── MetaClassTest
            │   ├── MetaObjectTest
            │   ├── ParamNameResolverTest
            │   ├── property
            │   │   ├── PropertyCopierTest
            │   │   ├── PropertyTokenizerTest
            │   │   └── SourceBeanCopierData
            │   ├── ReflectorTest
            │   ├── typeparam
            │   │   ├── Calculator
            │   │   ├── Level0Mapper
            │   │   ├── Level1Mapper
            │   │   └── Level2Mapper
            │   ├── TypeParameterResolverTest
            │   └── wrapper
            │       ├── BeanWrapperTest
            │       ├── BeanWrapperUnitTest
            │       ├── CollectionWrapperUnitTest
            │       ├── MapWrapperTest
            │       ├── MapWrapperUnitTest
            │       └── ObjectWrapperBase
            ├── scripting
            │   ├── defaults
            │   │   └── DefaultParameterHandlerTest
            │   ├── LanguageDriverRegistryTest
            │   └── xmltags
            │       ├── OgnlCacheTest
            │       └── XMLScriptBuilderTest
            ├── session
            │   ├── AutoMappingUnknownColumnBehaviorTest
            │   ├── defaults
            │   │   ├── ExtendedSqlSession
            │   │   ├── ExtendedSqlSessionFactory
            │   │   ├── ExtendedSqlSessionFactoryBuilder
            │   │   └── ExtendedSqlSessionFactoryTest
            │   ├── SqlSessionManagerTest
            │   └── SqlSessionTest
            ├── submitted
            │   ├── ancestor_ref
            │   │   ├── AncestorRefTest
            │   │   ├── Author
            │   │   ├── Blog
            │   │   ├── Mapper
            │   │   ├── Reputation
            │   │   └── User
            │   ├── annotion_many_one_add_columnprefix
            │   │   ├── OneManyColumnPrefixTest
            │   │   ├── Role
            │   │   ├── RoleDao
            │   │   ├── User
            │   │   └── UserDao
            │   ├── annotion_many_one_add_resultmapid
            │   │   ├── OneManyResultMapTest
            │   │   ├── Role
            │   │   ├── RoleDao
            │   │   ├── User
            │   │   └── UserDao
            │   ├── arg_name_based_constructor_automapping
            │   │   ├── ArgNameBasedConstructorAutoMappingTest
            │   │   ├── Mapper
            │   │   ├── Task
            │   │   ├── User
            │   │   └── User2
            │   ├── array_result_type
            │   │   ├── ArrayResultTypeTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── array_type_handler
            │   │   ├── ArrayTypeHandlerTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── association_nested
            │   │   ├── Folder
            │   │   ├── FolderFlatTree
            │   │   ├── FolderMapper
            │   │   └── FolderMapperTest
            │   ├── associationtest
            │   │   ├── AssociationTest
            │   │   ├── Brakes
            │   │   ├── Car
            │   │   ├── Engine
            │   │   └── Mapper
            │   ├── associationtype
            │   │   └── AssociationTypeTest
            │   ├── auto_type_from_non_ambiguous_constructor
            │   │   ├── Account
            │   │   ├── Account1
            │   │   ├── Account2
            │   │   ├── Account3
            │   │   ├── Account4
            │   │   ├── AutoTypeFromNonAmbiguousConstructorFailingTest
            │   │   ├── AutoTypeFromNonAmbiguousConstructorTest
            │   │   ├── FailingMapper
            │   │   ├── Mapper
            │   │   └── Mapper1
            │   ├── autodiscover
            │   │   ├── aliases
            │   │   │   └── DummyTypeAlias
            │   │   ├── AutodiscoverTest
            │   │   ├── handlers
            │   │   │   └── DummyTypeHandler
            │   │   └── mappers
            │   │       └── DummyMapper
            │   ├── automapping
            │   │   ├── Article
            │   │   ├── AutomappingTest
            │   │   ├── Book
            │   │   ├── Breeder
            │   │   ├── Mapper
            │   │   ├── Pet
            │   │   └── User
            │   ├── awful_table
            │   │   ├── AwfulTable
            │   │   ├── AwfulTableMapper
            │   │   └── AwfulTableTest
            │   ├── basetest
            │   │   ├── BaseTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── batch_keys
            │   │   ├── BatchKeysTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── batch_test
            │   │   ├── BatchTest
            │   │   ├── Dept
            │   │   ├── Mapper
            │   │   └── User
            │   ├── bind_in_foreach
            │   │   ├── BindInForeachTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── blobtest
            │   │   ├── BlobMapper
            │   │   ├── BlobRecord
            │   │   └── BlobTest
            │   ├── blocking_cache
            │   │   ├── BlockingCacheTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── bringrags
            │   │   ├── SimpleChildObject
            │   │   ├── SimpleChildObjectMapper
            │   │   ├── SimpleObject
            │   │   └── SimpleObjectTest
            │   ├── cache
            │   │   ├── CacheTest
            │   │   ├── CustomCache
            │   │   ├── CustomCacheMapper
            │   │   ├── ImportantPersonMapper
            │   │   ├── Person
            │   │   ├── PersonMapper
            │   │   └── SpecialPersonMapper
            │   ├── cacheorder
            │   │   ├── CacheOrderTest
            │   │   └── User
            │   ├── call_setters_on_nulls
            │   │   ├── CallSettersOnNullsTest
            │   │   ├── DoNotCallSettersOnNullsTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── call_setters_on_nulls_again
            │   │   ├── ChildBean
            │   │   ├── MyBatisTest
            │   │   └── ParentBean
            │   ├── camelcase
            │   │   ├── Camel
            │   │   └── CamelCaseMappingTest
            │   ├── cglib_lazy_error
            │   │   ├── CglibNPELazyTest
            │   │   ├── CglibNPETest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── choosewhen
            │   │   ├── ChooseWhenMapper
            │   │   ├── ChooseWhenTest
            │   │   └── User
            │   ├── collection_in_constructor
            │   │   ├── Aisle
            │   │   ├── Clerk
            │   │   ├── CollectionInConstructorObjectFactory
            │   │   ├── CollectionInConstructorTest
            │   │   ├── Container
            │   │   ├── Container1
            │   │   ├── CsvToListTypeHandler
            │   │   ├── Mapper
            │   │   ├── Store
            │   │   ├── Store10
            │   │   ├── Store2
            │   │   ├── Store3
            │   │   ├── Store4
            │   │   ├── Store5
            │   │   ├── Store6
            │   │   ├── Store7
            │   │   ├── Store8
            │   │   └── Store9
            │   ├── collection_injection
            │   │   ├── CollectionInjectionTest
            │   │   ├── immutable
            │   │   │   ├── HousePortfolio
            │   │   │   ├── ImmutableDefect
            │   │   │   ├── ImmutableFurniture
            │   │   │   ├── ImmutableHouse
            │   │   │   ├── ImmutableHouseMapper
            │   │   │   ├── ImmutableRoom
            │   │   │   └── ImmutableRoomDetail
            │   │   └── property
            │   │       ├── Defect
            │   │       ├── Furniture
            │   │       ├── House
            │   │       ├── HouseMapper
            │   │       ├── Room
            │   │       └── RoomDetail
            │   ├── collectionparameters
            │   │   ├── CollectionParametersTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── column_forwarding
            │   │   ├── ColumnForwardingTest
            │   │   ├── Group
            │   │   ├── Mapper
            │   │   └── User
            │   ├── column_order_based_constructor_automapping
            │   │   ├── ColumnOrderBasedConstructorAutomappingTest
            │   │   ├── Mapper
            │   │   ├── UserConstructorEqualsResultSet
            │   │   ├── UserConstructorGreaterThanResultSet
            │   │   ├── UserConstructorLessThanResultSet
            │   │   └── UserNoArgsConstructor
            │   ├── column_prefix
            │   │   ├── Address
            │   │   ├── AddressWithCaution
            │   │   ├── Brand
            │   │   ├── ColumnPrefixAutoMappingTest
            │   │   ├── ColumnPrefixNestedQueryTest
            │   │   ├── ColumnPrefixTest
            │   │   ├── Person
            │   │   ├── Pet
            │   │   ├── Phone
            │   │   ├── Product
            │   │   ├── Room
            │   │   └── Zip
            │   ├── complex_column
            │   │   ├── ComplexColumnTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── complex_property
            │   │   ├── ComponentTest
            │   │   ├── EncryptedString
            │   │   └── User
            │   ├── complex_type
            │   │   ├── ComplexTypeTest
            │   │   ├── Item
            │   │   └── Property
            │   ├── constructor_automapping
            │   │   ├── Article
            │   │   ├── Author
            │   │   ├── ConstructorAutomappingTest
            │   │   └── Mapper
            │   ├── constructor_columnprefix
            │   │   ├── Article
            │   │   ├── Author
            │   │   ├── ConstructorColumnPrefixTest
            │   │   ├── EntityKey
            │   │   └── Mapper
            │   ├── count
            │   │   ├── CountMapper
            │   │   └── CountTest
            │   ├── criterion
            │   │   ├── Criterion
            │   │   ├── CriterionTest
            │   │   └── Parameter
            │   ├── cursor_cache_oom
            │   │   ├── CursorOomTest
            │   │   ├── Friend
            │   │   ├── Mapper
            │   │   └── User
            │   ├── cursor_nested
            │   │   ├── CursorNestedTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── cursor_simple
            │   │   ├── AnnotationMapper
            │   │   ├── CursorSimpleTest
            │   │   ├── Mapper
            │   │   ├── MysqlCursorTest
            │   │   ├── PostgresCursorTest
            │   │   └── User
            │   ├── custom_collection_handling
            │   │   ├── Contact
            │   │   ├── CustomCollection
            │   │   ├── CustomCollectionHandlingTest
            │   │   ├── CustomObjectFactory
            │   │   ├── CustomObjectWrapper
            │   │   ├── CustomObjectWrapperFactory
            │   │   └── Person
            │   ├── databaseid_productname
            │   │   ├── DatabaseIdProductNameTest
            │   │   └── Mapper
            │   ├── default_method
            │   │   ├── DefaultMethodTest
            │   │   ├── Mapper
            │   │   ├── PackageMapper
            │   │   └── User
            │   ├── deferload_common_property
            │   │   ├── Child
            │   │   ├── ChildMapper
            │   │   ├── CommonPropertyDeferLoadTest
            │   │   ├── Father
            │   │   └── FatherMapper
            │   ├── dirty_select
            │   │   ├── DirtySelectTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── disallowdotsonnames
            │   │   ├── DisallowDotsOnNamesTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── discriminator
            │   │   ├── Car
            │   │   ├── Contract
            │   │   ├── DiscriminatorTest
            │   │   ├── Mapper
            │   │   ├── Owner
            │   │   ├── Truck
            │   │   └── Vehicle
            │   ├── dml_return_types
            │   │   ├── DmlMapperReturnTypesTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── duplicate_resource_loaded
            │   │   ├── DuplicateResourceTest
            │   │   └── Mapper
            │   ├── duplicate_statements
            │   │   ├── AnnotatedMapper
            │   │   ├── AnnotatedMapperExtended
            │   │   ├── DuplicateStatementsTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── dynsql
            │   │   ├── CustomUtil
            │   │   ├── DynSqlMapper
            │   │   ├── DynSqlTest
            │   │   ├── NumericRow
            │   │   └── Parameter
            │   ├── dynsql2
            │   │   ├── DynSqlTest
            │   │   ├── FirstNameTypeHandler
            │   │   ├── LastNameTypeHandler
            │   │   ├── Name
            │   │   └── Parameter
            │   ├── empty_namespace
            │   │   ├── EmptyNamespaceTest
            │   │   └── Person
            │   ├── empty_row
            │   │   ├── Child
            │   │   ├── ImmutableParent
            │   │   ├── Mapper
            │   │   ├── Parent
            │   │   ├── Pet
            │   │   └── ReturnInstanceForEmptyRowTest
            │   ├── emptycollection
            │   │   ├── Dao
            │   │   ├── DaoTest
            │   │   ├── TodoItem
            │   │   └── TodoLists
            │   ├── encoding
            │   │   ├── EncodingMapper
            │   │   └── EncodingTest
            │   ├── enum_interface_type_handler
            │   │   ├── Color
            │   │   ├── EnumInterfaceTypeHandlerTest
            │   │   ├── HasValue
            │   │   ├── HasValueEnumTypeHandler
            │   │   ├── Mapper
            │   │   ├── User
            │   │   └── XmlMapper
            │   ├── enum_with_method
            │   │   ├── Currency
            │   │   ├── EnumWithMethodTest
            │   │   ├── Mapper
            │   │   ├── Mood
            │   │   ├── MoodTypeTypeHandler
            │   │   └── User
            │   ├── enumtypehandler_on_annotation
            │   │   ├── Employee
            │   │   ├── EnumTypeHandlerUsingAnnotationTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── enumtypehandler_on_map
            │   │   ├── EnumTypeHandlerTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── extend
            │   │   ├── Child
            │   │   ├── ExtendMapper
            │   │   ├── ExtendTest
            │   │   └── Parent
            │   ├── extendresultmap
            │   │   ├── ExtendResultMapTest
            │   │   ├── TestMapperX
            │   │   ├── TestMapperY
            │   │   └── TestModel
            │   ├── extends_with_constructor
            │   │   ├── NpeExtendsTest
            │   │   ├── Student
            │   │   ├── StudentConstructor
            │   │   ├── StudentConstructorMapper
            │   │   ├── StudentMapper
            │   │   ├── Teacher
            │   │   └── TeacherMapper
            │   ├── flush_statement_npe
            │   │   ├── FlushStatementNpeTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── force_flush_on_select
            │   │   ├── ForceFlushOnSelectTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── foreach
            │   │   ├── ForEachTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── foreach_map
            │   │   ├── ForEachMapTest
            │   │   ├── IntBoolMapEntry
            │   │   ├── MapParam
            │   │   ├── NestedBean
            │   │   ├── NestedBeanMapEntry
            │   │   └── StringStringMapEntry
            │   ├── generictyperesolution
            │   │   ├── Entity
            │   │   ├── GenericTypeResolutionTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── generictypes
            │   │   ├── GenericTypesTest
            │   │   ├── Group
            │   │   ├── Mapper
            │   │   ├── User
            │   │   └── UserTypeHandler
            │   ├── global_variables
            │   │   ├── AnnotationMapper
            │   │   ├── BaseTest
            │   │   ├── CustomCache
            │   │   ├── Mapper
            │   │   └── User
            │   ├── global_variables_defaults
            │   │   ├── AnnotationMapperTest
            │   │   ├── ConfigurationTest
            │   │   ├── CustomizationTest
            │   │   ├── SupportClasses
            │   │   └── XmlMapperTest
            │   ├── handle_by_jdbc_type
            │   │   ├── BooleanCharTypeHandler
            │   │   ├── BooleanIntTypeHandler
            │   │   ├── BoolsBean
            │   │   ├── HandlerByJdbcTypeTest
            │   │   └── Mapper
            │   ├── hashmaptypehandler
            │   │   ├── HashMapTypeHandler
            │   │   ├── HashMapTypeHandlerTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── heavy_initial_load
            │   │   ├── Code
            │   │   ├── HeavyInitialLoadTest
            │   │   ├── Thing
            │   │   └── ThingMapper
            │   ├── immutable_constructor
            │   │   ├── ImmutablePOJO
            │   │   ├── ImmutablePOJOMapper
            │   │   └── ImmutablePOJOTest
            │   ├── include_property
            │   │   ├── DuplicatedIncludePropertiesMapper
            │   │   ├── IncludePropertyErrorTest
            │   │   └── IncludePropertyTest
            │   ├── includes
            │   │   └── IncludeTest
            │   ├── inheritance
            │   │   ├── BaseMapper
            │   │   ├── InheritanceTest
            │   │   ├── UserProfile
            │   │   └── UserProfileMapper
            │   ├── initialized_collection_property
            │   │   ├── Author
            │   │   ├── AuthorDAOTest
            │   │   └── Post
            │   ├── inline_association_with_dot
            │   │   ├── Element
            │   │   ├── ElementMapper
            │   │   ├── ElementMapperUsingInline
            │   │   ├── ElementMapperUsingSubMap
            │   │   └── InlineCollectionWithDotTest
            │   ├── integer_enum
            │   │   ├── IntegerEnumTest
            │   │   └── Record
            │   ├── javassist
            │   │   ├── Group
            │   │   ├── JavassistTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── keycolumn
            │   │   ├── InsertMapper
            │   │   ├── InsertTest
            │   │   └── Name
            │   ├── keygen
            │   │   ├── Country
            │   │   ├── CountryMapper
            │   │   ├── Jdbc3KeyGeneratorTest
            │   │   ├── NpeCountry
            │   │   └── Planet
            │   ├── language
            │   │   ├── LanguageTest
            │   │   ├── Mapper
            │   │   ├── Name
            │   │   ├── Parameter
            │   │   ├── VelocityLanguageDriver
            │   │   ├── VelocitySqlSource
            │   │   └── VelocitySqlSourceBuilder
            │   ├── lazy_deserialize
            │   │   ├── LazyDeserializeTest
            │   │   ├── LazyObjectBar
            │   │   ├── LazyObjectFoo
            │   │   └── Mapper
            │   ├── lazy_immutable
            │   │   ├── ImmutablePOJO
            │   │   ├── ImmutablePOJOMapper
            │   │   └── ImmutablePOJOTest
            │   ├── lazy_properties
            │   │   ├── LazyPropertiesTest
            │   │   ├── Mapper
            │   │   └── User
            │   ├── lazyload_common_property
            │   │   ├── Child
            │   │   ├── ChildMapper
            │   │   ├── CommonPropertyLazyLoadTest
            │   │   ├── Father
            │   │   ├── FatherMapper
            │   │   ├── GrandFather
            │   │   └── GrandFatherMapper
            │   ├── lazyload_proxyfactory_comparison
            │   │   ├── AbstractLazyTest
            │   │   ├── CglibLazyTest
            │   │   ├── DefaultLazyTest
            │   │   ├── Group
            │   │   ├── JavassistLazyTest
            │   │   ├── Mapper
            │   │   ├── Owned
            │   │   ├── UserWithGetObjectWithInterface
            │   │   ├── UserWithGetObjectWithoutInterface
            │   │   ├── UserWithGetXxxWithInterface
            │   │   ├── UserWithGetXxxWithoutInterface
            │   │   ├── UserWithNothingWithInterface
            │   │   └── UserWithNothingWithoutInterface
            │   ├── literal_string
            │   │   ├── LiteralStringTest
            │   │   └── Mapper
            │   ├── localtime
            │   │   ├── LocalTimeTest
            │   │   ├── Mapper
            │   │   └── Record
            │   ├── manyanno
            │   │   ├── AnnoPost
            │   │   ├── AnnoPostTag
            │   │   ├── ManyAnnoTest
            │   │   └── PostMapper
            │   ├── map_class_name_conflict
            │   │   ├── MapperNameTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── mapper_extend
            │   │   ├── ChildMapper
            │   │   ├── GrandpaMapper
            │   │   ├── Mapper
            │   │   ├── MapperExtendTest
            │   │   ├── MapperOverload
            │   │   ├── ParentMapper
            │   │   └── User
            │   ├── mapper_type_parameter
            │   │   ├── BaseMapper
            │   │   ├── Country
            │   │   ├── CountryMapper
            │   │   ├── MapperTypeParameterTest
            │   │   ├── Person
            │   │   ├── PersonListMapper
            │   │   └── PersonMapper
            │   ├── maptypehandler
            │   │   ├── LabelsTypeHandler
            │   │   ├── Mapper
            │   │   ├── MapTypeHandlerTest
            │   │   └── User
            │   ├── member_access
            │   │   └── MemberAccessTest
            │   ├── missing_id_property
            │   │   ├── Car
            │   │   ├── CarMapper
            │   │   ├── MissingIdPropertyTest
            │   │   └── Part
            │   ├── multidb
            │   │   ├── DummyDatabaseIdProvider
            │   │   ├── MultiDbMapper
            │   │   ├── MultiDbTest
            │   │   ├── ProviderTest
            │   │   └── User
            │   ├── multiple_discriminator
            │   │   ├── Director
            │   │   ├── Employee
            │   │   ├── MultipleDiscriminatorTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── multiple_resultsets
            │   │   ├── Mapper
            │   │   ├── MultipleResultTest
            │   │   ├── OrderDetail
            │   │   └── OrderHeader
            │   ├── multipleiterates
            │   │   ├── Mapper
            │   │   ├── MultipleIteratesTest
            │   │   └── User
            │   ├── multipleresultsetswithassociation
            │   │   ├── Mapper
            │   │   ├── MultipleResultSetTest
            │   │   ├── OrderDetail
            │   │   └── OrderHeader
            │   ├── named_constructor_args
            │   │   ├── InvalidNamedConstructorArgsTest
            │   │   ├── Mapper
            │   │   ├── NamedConstructorArgsTest
            │   │   ├── NamedConstructorArgsUseActualNameTest
            │   │   ├── UseActualNameMapper
            │   │   └── User
            │   ├── nested
            │   │   ├── Mapper
            │   │   ├── Name
            │   │   ├── NestedForEachTest
            │   │   └── Parameter
            │   ├── nested_query_cache
            │   │   ├── AuthorMapper
            │   │   ├── BlogMapper
            │   │   └── NestedQueryCacheTest
            │   ├── nestedresulthandler
            │   │   ├── Item
            │   │   ├── Mapper
            │   │   ├── NestedResultHandlerTest
            │   │   ├── Person
            │   │   └── PersonItemPair
            │   ├── nestedresulthandler_association
            │   │   ├── Account
            │   │   ├── AccountAddress
            │   │   └── NestedResultHandlerAssociationTest
            │   ├── nestedresulthandler_gh1551
            │   │   ├── NestedResultHandlerGh1551Test
            │   │   ├── ProductInfo
            │   │   ├── ProductMapper
            │   │   ├── ProductResp
            │   │   └── ProductSku
            │   ├── nestedresulthandler_multiple_association
            │   │   ├── Binome
            │   │   ├── ChildBean
            │   │   ├── NestedResultHandlerMultipleAssociationTest
            │   │   └── ParentBean
            │   ├── no_param_type
            │   │   ├── NoParamTypeTest
            │   │   └── User
            │   ├── no_result_type_map
            │   │   ├── Mapper
            │   │   ├── NoResultTypeMapTest
            │   │   ├── ParentMapper
            │   │   └── User
            │   ├── nonexistentvariables
            │   │   ├── Mapper
            │   │   └── NonExistentVariablesTest
            │   ├── not_null_column
            │   │   ├── Base
            │   │   ├── Child
            │   │   ├── Father
            │   │   ├── FatherMapper
            │   │   └── NotNullColumnTest
            │   ├── null_associations
            │   │   ├── Bar
            │   │   ├── Foo
            │   │   ├── FooMapper
            │   │   └── FooMapperTest
            │   ├── ognl_enum
            │   │   ├── EnumWithOgnlTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── ognlstatic
            │   │   ├── Mapper
            │   │   ├── OgnlStaticTest
            │   │   ├── StaticClass
            │   │   └── User
            │   ├── optional_on_mapper_method
            │   │   ├── Mapper
            │   │   ├── OptionalOnMapperMethodTest
            │   │   └── User
            │   ├── oracle_cursor
            │   │   ├── Author
            │   │   ├── Author2
            │   │   ├── Book
            │   │   ├── Book2
            │   │   ├── BooksTypeHandler
            │   │   ├── Mapper
            │   │   └── OracleCursorTest
            │   ├── order_prefix_removed
            │   │   ├── OrderPrefixRemovedTest
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── orphan_result_maps
            │   │   ├── Blog
            │   │   ├── NestedCollectionMapper
            │   │   ├── OrphanResultMapTest
            │   │   ├── Post
            │   │   └── SeparateCollectionMapper
            │   ├── overwritingproperties
            │   │   ├── Bar
            │   │   ├── Foo
            │   │   ├── FooMapper
            │   │   └── FooMapperTest
            │   ├── param_name_resolve
            │   │   ├── ActualParamNameTest
            │   │   └── NoActualParamNameTest
            │   ├── parametrizedlist
            │   │   ├── Mapper
            │   │   ├── ParametrizedListTest
            │   │   └── User
            │   ├── parent_childs
            │   │   ├── Child
            │   │   ├── Mapper
            │   │   ├── Parent
            │   │   └── ParentChildTest
            │   ├── parent_reference_3level
            │   │   ├── Blog
            │   │   ├── BlogTest
            │   │   ├── Comment
            │   │   ├── Mapper
            │   │   └── Post
            │   ├── permissions
            │   │   ├── Permission
            │   │   ├── PermissionsMapper
            │   │   ├── PermissionsTest
            │   │   ├── Principal
            │   │   └── Resource
            │   ├── postgres_genkeys
            │   │   ├── Mapper
            │   │   ├── PostgresGeneratedKeysTest
            │   │   ├── Section
            │   │   └── User
            │   ├── primitive_array
            │   │   ├── Mapper
            │   │   ├── PrimitiveArrayTest
            │   │   └── User
            │   ├── primitive_result_type
            │   │   ├── IbatisConfig
            │   │   ├── PrimitiveResultTypeTest
            │   │   ├── Product
            │   │   ├── ProductDAO
            │   │   └── ProductMapper
            │   ├── primitives
            │   │   ├── Assetright
            │   │   ├── Mapper
            │   │   └── PrimitivesTest
            │   ├── propertiesinmapperfiles
            │   │   ├── Mapper
            │   │   ├── PropertiesInMappersTest
            │   │   └── User
            │   ├── quotedcolumnnames
            │   │   └── QuotedColumnNamesTest
            │   ├── raw_sql_source
            │   │   ├── RawSqlSourceTest
            │   │   └── User
            │   ├── record_type
            │   │   ├── Item
            │   │   ├── Property
            │   │   ├── RecordTypeMapper
            │   │   └── RecordTypeTest
            │   ├── refcursor
            │   │   ├── Order
            │   │   ├── OrderDetail
            │   │   ├── OrdersMapper
            │   │   └── RefCursorTest
            │   ├── refid_resolution
            │   │   ├── ExternalRefidResolutionTest
            │   │   └── RefidResolutionTest
            │   ├── repeatable
            │   │   ├── BothSelectAndSelectProviderMapper
            │   │   ├── BothSelectContainerAndSelectProviderContainerMapper
            │   │   ├── Mapper
            │   │   ├── NoDefineDefaultDatabaseMapper
            │   │   ├── RepeatableDeleteTest
            │   │   ├── RepeatableErrorTest
            │   │   ├── RepeatableInsertTest
            │   │   ├── RepeatableSelectTest
            │   │   ├── RepeatableUpdateTest
            │   │   └── User
            │   ├── resolution
            │   │   ├── cachereffromxml
            │   │   │   ├── CacheRefFromXmlTest
            │   │   │   └── UserMapper
            │   │   ├── cacherefs
            │   │   │   ├── CacheRefsTest
            │   │   │   └── MapperB
            │   │   ├── deepresultmap
            │   │   │   ├── DeepResultMapTest
            │   │   │   └── MapperA
            │   │   ├── javamethods
            │   │   │   ├── JavaMethodsTest
            │   │   │   ├── MapperA
            │   │   │   ├── MapperB
            │   │   │   └── MapperC
            │   │   └── User
            │   ├── result_handler
            │   │   ├── Mapper
            │   │   ├── ResultHandlerTest
            │   │   ├── User
            │   │   └── UserResultHandler
            │   ├── result_handler_type
            │   │   ├── DefaultResultHandlerTypeTest
            │   │   ├── ObjectFactory
            │   │   ├── Person
            │   │   └── PersonMapper
            │   ├── result_set_type
            │   │   ├── Mapper
            │   │   ├── ResultSetTypeTest
            │   │   └── User
            │   ├── resultmapwithassociationstest
            │   │   ├── Address
            │   │   ├── Mapper
            │   │   ├── Person
            │   │   └── ResultMapWithAssociationsTest
            │   ├── results_id
            │   │   ├── AnotherMapper
            │   │   ├── IdConflictMapper
            │   │   ├── IdConflictTest
            │   │   ├── Mapper
            │   │   ├── ResultsIdTest
            │   │   └── User
            │   ├── rounding
            │   │   ├── Mapper
            │   │   ├── RoundingHandlersTest
            │   │   └── User
            │   ├── selectkey
            │   │   ├── AnnotatedMapper
            │   │   ├── Name
            │   │   ├── SelectKeyTest
            │   │   └── SqlProvider
            │   ├── serializecircular
            │   │   ├── Attribute
            │   │   ├── AttributeMapper
            │   │   ├── Department
            │   │   ├── DepartmentMapper
            │   │   ├── Person
            │   │   ├── PersonMapper
            │   │   ├── SerializeCircularTest
            │   │   └── UtilityTester
            │   ├── simplelistparameter
            │   │   ├── Car
            │   │   ├── CarMapper
            │   │   ├── Rv
            │   │   ├── SimpleListParameterTest
            │   │   └── Vehicle
            │   ├── sptests
            │   │   ├── Book
            │   │   ├── Genre
            │   │   ├── Item
            │   │   ├── Name
            │   │   ├── Parameter
            │   │   ├── SPMapper
            │   │   └── SPTest
            │   ├── sql
            │   │   ├── HsqldbSQLTest
            │   │   ├── Mapper
            │   │   ├── PostgresSQLTest
            │   │   └── User
            │   ├── sqlprovider
            │   │   ├── BaseMapper
            │   │   ├── Mapper
            │   │   ├── OurSqlBuilder
            │   │   ├── ProviderMethodResolutionTest
            │   │   ├── SqlProviderTest
            │   │   └── User
            │   ├── stringlist
            │   │   ├── Mapper
            │   │   ├── StringListTest
            │   │   └── User
            │   ├── substitution_in_annots
            │   │   ├── SubstitutionInAnnotsMapper
            │   │   └── SubstitutionInAnnotsTest
            │   ├── timestamp_with_timezone
            │   │   ├── Mapper
            │   │   ├── Record
            │   │   └── TimestampWithTimezoneTypeHandlerTest
            │   ├── timezone_edge_case
            │   │   ├── Mapper
            │   │   ├── Record
            │   │   └── TimezoneEdgeCaseTest
            │   ├── typebasedtypehandlerresolution
            │   │   ├── CsvTypeHandler
            │   │   ├── FuzzyBean
            │   │   ├── GloballyRegisteredHandlerMapper
            │   │   ├── GloballyRegisteredTypeHandlerResolutionTest
            │   │   ├── LocallySpecifiedHandlerMapper
            │   │   ├── LocallySpecifiedTypeHandlerResolutionTest
            │   │   ├── ParentBean
            │   │   ├── Product
            │   │   ├── TypeAwareTypeHandler
            │   │   └── User
            │   ├── typehandler
            │   │   ├── Mapper
            │   │   ├── Product
            │   │   ├── StringTrimmingTypeHandler
            │   │   ├── TypeHandlerTest
            │   │   ├── User
            │   │   └── VagueBean
            │   ├── typehandlerinjection
            │   │   ├── Mapper
            │   │   ├── TypeHandlerInjectionTest
            │   │   ├── User
            │   │   └── UserStateTypeHandler
            │   ├── unknownobject
            │   │   ├── Mapper
            │   │   ├── UnknownObject
            │   │   ├── UnknownObjectTest
            │   │   └── User
            │   ├── unmatched_prop_type
            │   │   ├── UnmatchedPropTypeMapper
            │   │   ├── UnmatchedPropTypeTest
            │   │   └── User
            │   ├── use_actual_param_name
            │   │   ├── Mapper
            │   │   ├── UseActualParamNameTest
            │   │   └── User
            │   ├── uuid_test
            │   │   ├── Mapper
            │   │   ├── User
            │   │   ├── UUIDTest
            │   │   └── UUIDTypeHandler
            │   ├── valueinmap
            │   │   └── ValueInMapTest
            │   ├── xml_external_ref
            │   │   ├── Dog
            │   │   ├── InvalidMapper
            │   │   ├── InvalidWithInsertMapper
            │   │   ├── MultipleCrossIncludePersonMapper
            │   │   ├── MultipleCrossIncludePetMapper
            │   │   ├── MultipleCrossIncludeTest
            │   │   ├── MultipleIncludePersonMapper
            │   │   ├── MultipleIncludeTest
            │   │   ├── MultipleReverseIncludePersonMapper
            │   │   ├── MultipleReverseIncludeTest
            │   │   ├── NonFullyQualifiedNamespaceTest
            │   │   ├── ParameterMapReferencePersonMapper
            │   │   ├── ParameterMapReferencePetMapper
            │   │   ├── ParameterMapReferenceTest
            │   │   ├── Person
            │   │   ├── PersonMapper
            │   │   ├── Pet
            │   │   ├── PetMapper
            │   │   ├── ResultMapExtendsTest
            │   │   ├── ResultMapReferencePersonMapper
            │   │   ├── ResultMapReferencePetMapper
            │   │   ├── ResultMapReferenceTest
            │   │   ├── ReverseIncludePersonMapper
            │   │   ├── ReverseIncludeTest
            │   │   ├── SameIdPersonMapper
            │   │   ├── SameIdPetMapper
            │   │   ├── SameIdTest
            │   │   ├── ShortNameTest
            │   │   └── XmlExternalRefTest
            │   └── xml_references
            │       ├── EnumWithOgnlTest
            │       ├── Person
            │       ├── PersonMapper
            │       └── PersonMapper2
            ├── testcontainers
            │   ├── MysqlContainer
            │   ├── OracleTestContainer
            │   └── PgContainer
            ├── transaction
            │   ├── jdbc
            │   │   ├── JdbcTransactionBase
            │   │   ├── JdbcTransactionFactoryTest
            │   │   ├── JdbcTransactionFactoryUnitTest
            │   │   ├── JdbcTransactionTest
            │   │   ├── JdbcTransactionWithConnectionTest
            │   │   ├── JdbcTransactionWithDataSourceTest
            │   │   └── TestConnection
            │   ├── managed
            │   │   ├── ManagedTransactionBase
            │   │   ├── ManagedTransactionFactoryTest
            │   │   ├── ManagedTransactionFactoryUnitTest
            │   │   ├── ManagedTransactionWithConnectionTest
            │   │   └── ManagedTransactionWithDataSourceTest
            │   └── TransactionFactoryBase
            └── type
                ├── ArrayTypeHandlerTest
                ├── ✅ BaseTypeHandlerTest: 只是一个基础测试抽象类，封装了几个抽象方法
                ├── BigDecimalTypeHandlerTest
                ├── BigIntegerTypeHandlerTest
                ├── BlobByteObjectArrayTypeHandlerTest
                ├── BlobInputStreamTypeHandlerTest
                ├── BlobTypeHandlerTest
                ├── BooleanTypeHandlerTest
                ├── ByteArrayTypeHandlerTest
                ├── ByteObjectArrayTypeHandlerTest
                ├── ✅ ByteTypeHandlerTest
                ├── CharacterTypeHandlerTest
                ├── ClobReaderTypeHandlerTest
                ├── ClobTypeHandlerTest
                ├── DateOnlyTypeHandlerTest
                ├── DateTypeHandlerTest
                ├── DoubleTypeHandlerTest
                ├── EnumOrdinalTypeHandlerTest
                ├── EnumTypeHandlerTest
                ├── FloatTypeHandlerTest
                ├── InstantTypeHandlerTest
                ├── ✅ IntegerTypeHandlerTest: 对 结果集/预编译/存储过程 能获取结果/获取不到结果 两个场景进行测试/Mock
                ├── JapaneseDateTypeHandlerTest
                ├── ✅ JdbcTypeTest: 只是对 Java.sql.Types 的常量进行测试
                ├── Jsr310TypeHandlerRegistryTest
                ├── LocalDateTimeTypeHandlerTest
                ├── LocalDateTypeHandlerTest
                ├── LocalTimeTypeHandlerTest
                ├── ✅ LongTypeHandlerTest
                ├── MonthTypeHandlerTest
                ├── NClobTypeHandlerTest
                ├── NStringTypeHandlerTest
                ├── ObjectTypeHandlerTest
                ├── OffsetDateTimeTypeHandlerTest
                ├── OffsetTimeTypeHandlerTest
                ├── ShortTypeHandlerTest
                ├── SimpleTypeRegistryTest
                ├── SqlDateTypeHandlerTest
                ├── SqlTimestampTypeHandlerTest
                ├── SqlTimeTypeHandlerTest
                ├── SqlxmlTypeHandlerTest
                ├── StringTypeHandlerTest
                ├── TimeOnlyTypeHandlerTest
                ├── ✅ TypeAliasRegistryTest
                ├── TypeHandlerRegistryTest
                ├── TypeReferenceTest
                ├── UnknownTypeHandlerTest
                ├── YearMonthTypeHandlerTest
                ├── YearTypeHandlerTest
                └── ZonedDateTimeTypeHandlerTest

235 directories, 1001 files

```